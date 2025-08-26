
# Express CRUD Learning

A simple learning project: a blog-style CRUD (Create, Read, Update, Delete) app built with **Node.js**, **Express**, and **EJS**. It’s designed to help you practice RESTful routing, templating, and basic form handling.

---

##  Key Features
- Create new posts
- View all posts
- View individual post details
- Edit posts
- (Optional future) Delete posts
- Uses **UUID** for unique IDs
- Implements **PATCH** request via `method-override`

---

##  Tech Stack
- **Node.js** for the server runtime  
- **Express.js** for handling routing and middleware  
- **EJS** as the view engine for templating  
- **UUID** to generate unique IDs  
- **method-override** to support HTTP verbs like PATCH and DELETE  

---

##  Project Structure
```

express-crud-learning/
├── public/                 # Static files (CSS, JavaScript, images)
├── views/                  # EJS templates
│   ├── index.ejs           # Display all posts
│   ├── new\.ejs             # Form to create a new post
│   ├── show\.ejs            # Display single post
│   └── edit.ejs            # Form to edit a post
├── index.js                # Main application server file
├── package.json
├── package-lock.json
└── .gitignore

````

---

##  Getting Started

1. **Clone the repository**  
   ```bash
   git clone https://github.com/mishra-khushboo/express-crud-learning.git
   cd express-crud-learning
````

2. **Install dependencies**

   ```bash
   npm install
   ```

3. **Run the application**

   ```bash
   npm start
   ```

   *(Or `node index.js` if you haven’t defined a start script.)*

4. **Open your browser**
   Navigate to `http://localhost:8080`

---

## Usage

* **Create a post**: Navigate to `/posts/new`, fill out and submit the form.
* **View posts**: `/posts` shows a list of all posts.
* **Edit a post**: Click “Edit” on a post—this takes you to `/posts/:id/edit`.
* *(Future)* **Delete a post**: Add delete functionality using method-override.

---

## Future Improvements

* Add **delete** functionality using `DELETE` via method-override
* Use a real **database** (like MongoDB or PostgreSQL) instead of in-memory array
* Add **user authentication** (login/logout)
* Enhance UI with CSS or frameworks like **Bootstrap** or **Tailwind**

---

## Contributing

Feel free to submit pull requests or suggestions. Happy coding and learning!
