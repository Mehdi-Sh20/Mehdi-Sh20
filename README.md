

# 📚 Book List Manager (React)

A modern React application for managing a list of books.  
Users can **add, view, edit, and delete books** through an interactive and responsive interface powered by a local API.

This project showcases **real-world React concepts**, including component architecture, asynchronous data handling, UI state management, and clean design patterns.

---

## 🚀 Features

-  Fetch and display books from a local API
-  Add new books via a modal form
-  Edit existing book details
-  Delete books from the list
-  Toggle book list visibility (Show / Hide)
-  Loading indicator during data fetching
-  Error handling for API requests
-  Dynamic status messages (add / edit / delete)
-  Fully responsive design (mobile-friendly)
-  Automatic UI updates using React state
-  Keyboard navigation using arrow keys, with visible focus highlighting  

---

## 🛠 Technologies Used

- **React**
- **JavaScript (ES6+)**
- **CSS Modules**
- **Fetch API**
- **JSON Server (Local API)**

---

## 📂 Project Structure


```
src
├── component
│  ├── Book-list-manager/
│  ├── event-item-list/
│  ├──events-list-btn-notifications/
│  ├── modalBox/
│  ├── modal-details/
│  ├── keyboard-nav-list/
│  ├── handle-event-button/
│  ├── footer/
│  └── title/
│
├── App.jsx
├── index.js
└── App.css
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the repository

```bash
git clone https://github.com/YOURGITHUBADDRESS/books-list-manager.git
cd books-list-manager
npm install
```


### 2️⃣ Run JSON Server (Local API)

```bash
npx json-server --watch db.json --port 3000
```

### 3️⃣ Start the React App

```bash
npm start
```

## 🌐 API Endpoint

```
http://localhost:3000/books
```

### 🔗 Live Demo

[View the Live Application](https://your-project-demo-link.com)
;; (Replace with your deployed link from Vercel / Netlify / GitHub Pages)

---

## 🧠 Key React Concepts Demonstrated

### 🔹 State Management

Using `useState` to manage UI and data state.

### 🔹 Side Effects

Using `useEffect` for data fetching and synchronization, updating data.

### 🔹 Async / Await

Handling asynchronous API calls in a clean and readable way.

### 🔹 Error Handling

Using try / catch for safe API operations.

### 🔹 Conditional Rendering

Displaying UI based on:

- loading state
- error state
- empty data
- success messages

### 🔹 Component Communication

Using:

 -  `forwardRef`
 -  `useImperativeHandle`

To trigger updates across components (e.g., success notifications).

## 🔄 Application Flow
1. Books are fetched from the API
2. Loading spinner is displayed during fetch
3. Users can:
    -  Add a new book (via modal)
    -  Edit an existing book
    -  Delete a books
4. After actions:
    -  Success message is shown
    -  UI updates automatically

---

## 🎨 UI Behavior
- 🔹 Loading spinner during API requests
- 🔹 Empty state message when no books exist
- 🔹 Feedback notifications after actions
- 🔹 Fully responsive design for mobile devices

---

## 🚧 Future Improvements

- 🔹 Persistent notification system (toast)
- 🔹 Advanced form validation
- 🔹 Global state management (React Context / Redux)
- 🔹 Search & filter books

--- 

## 📸 Screenshots

![Book List Manager Screenshot](image/book-list.jpg)

---

## 👨‍💻 Author

Developed as a React learning project to practice:

- Component architecture
- Async operations
- UI/UX improvements
- State management patterns

---

## 📄 License

This project is licensed under the MIT License.


