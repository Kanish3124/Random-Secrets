# 🔐 Secrets App

An Express.js application that fetches random secrets from a remote API and displays them dynamically on a web page. 🌟

---

## 🚀 Features

- 🔗 Fetches random secrets using the [Secrets API](https://secrets-api.appbrewery.com).
- 🖼️ Uses EJS for rendering dynamic content.
- 🌐 Serves static files with ease.

---

## 🛠️ Installation

1. Clone the repository:
   ```bash
   git clone <repository_url>
   ```

2. Navigate to the project directory:
   ```bash
   cd <project_directory>
   ```

3. Install dependencies:
   ```bash
   npm install
   ```

---

## 🏃 Usage

1. Start the server:
   ```bash
   node app.js
   ```

2. Open your browser and visit:
   ```
   http://localhost:3000
   ```

---

## 📂 Project Structure

```plaintext
├── public
│   └── css
│       └── styles.css       # Add your custom styles here
├── views
│   └── index.ejs            # EJS template to display the secret
├── index.js                   # Main application logic
├── package.json             # Project dependencies
└── README.md                # Documentation
```

---

## 📋 Requirements

- Node.js (v14 or higher)
- npm (v6 or higher)
- Internet connection for the Secrets API

---

## 🔧 Technologies Used

- **Express.js** - Backend framework for Node.js
- **Axios** - HTTP client for API requests
- **EJS** - Templating engine for dynamic content

---

## ✨ How It Works

1. The root route (`/`) fetches a random secret from the Secrets API.
2. The fetched data includes:
   - `secret`: The random secret message.
   - `username`: The username associated with the secret.
3. The data is rendered dynamically using an EJS template and displayed on the page.

---

## 🌐 API Reference

This app uses the [Secrets API](https://secrets-api.appbrewery.com):
- **Endpoint**: `/random`
- **Response Format**:
  ```json
  {
    "secret": "string",
    "username": "string"
  }
  ```

---

## 🤝 Contributing

Contributions are welcome! 🎉 Feel free to fork the repo, make changes, and submit a pull request. 💡

---

## 🙏 Acknowledgments

- [Express.js](https://expressjs.com/) for the robust backend framework.
- [Axios](https://axios-http.com/) for the seamless HTTP requests.
- [EJS](https://ejs.co/) for the dynamic templates.

---

### 👨‍💻 Author

Created by **Kanish**. ✨ Happy Coding! 🚀
