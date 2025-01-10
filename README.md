# Coding Arena 101 - Testcase Runner

**Website URL:** [Coding Arena 101 - Testcase Runner](https://coding-arena-testcase-runner.web.app/)

This project is a web-based platform designed for competitive programmers and developers to test and run their code against custom test cases. The application is built with a modern dark theme for an aesthetically pleasing and user-friendly experience.

---

## Features

1. **Testcase Management**  
   - Add multiple test cases (input/output).
   - Visual indicators for passed and failed test cases.

2. **Code Execution**  
   - Supports multiple programming languages (C, C++, Python, Java, JavaScript).
   - Uses Monaco Editor for a seamless coding experience.

3. **Dark Theme**  
   - A visually appealing dark theme with smooth animations and modern styling.

4. **Firebase Integration**  
   - Hosted using Firebase for reliable and fast performance.

5. **Toast Notifications**  
   - Get success and error feedback via Toastify notifications.

---

## Technologies Used

- **Frontend:** ReactJS, Monaco Editor
- **Styling:** CSS (Dark Theme)
- **Backend:** Firebase Hosting, Code Execution API

---

## Project Structure

```plaintext
.
├── public
├── src
│   ├── components
│   │   ├── CodeEditor.jsx    // Main editor component
│   │   ├── Testcase.jsx      // Testcase component
│   ├── styles
│   │   ├── CodeEditor.css    // Styling for the dark theme
│   ├── App.js                // Root component
│   ├── index.js              // Entry point
├── package.json
├── firebase.json             // Firebase configuration
└── README.md
```

---

## How to Run Locally

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/your-repo/coding-arena-testcase-runner.git
   cd coding-arena-testcase-runner
   ```

2. **Install Dependencies:**
   ```bash
   npm install
   ```

3. **Start the Development Server:**
   ```bash
   npm start
   ```

4. **Open in Browser:**
   Navigate to `http://localhost:3000`.

---

## Deployment

The application is hosted on Firebase. Follow these steps to deploy:

1. **Build the Application:**
   ```bash
   npm run build
   ```

2. **Deploy to Firebase:**
   ```bash
   firebase deploy
   ```

3. **Access the Live Website:**
   Visit [https://coding-arena-testcase-runner.web.app/](https://coding-arena-testcase-runner.web.app/).

---

## License

This project is licensed under the MIT License. See the [LICENSE](./LICENSE) file for details.

---

## Contributors

- **Lohit P Talavar**  
  Developer and Project Lead

---

## Acknowledgments

Special thanks to the open-source community for tools like ReactJS, Firebase, Monaco Editor, and Toastify.
