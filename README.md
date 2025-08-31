# The Atomic Blog

### [🚀 Live Demo](https://atomic-blog-demo.netlify.app)

## Project Description

The Atomic Blog is a simple React application built to **illustrate and practice React optimization techniques**, including useCallback, useMemo, and memoization(memo). While the future of React, particularly with the introduction of the React Compiler, aims to automate much of this optimization, a deep understanding of these manual techniques remains a fundamental skill.

<br>

## **🚨🚨 Note**

The primary purpose of this project is to showcase **performance optimization concepts** in React. For this reason, **responsive design was intentionally not implemented and the user interface, feature set are therefore deliberately simple**, allowing for a clear and isolated focus on the technical implementation of performance.

<br>

---

### Key Optimization Features

- `memo`
- `useCallback`
- `useMemo`

---

### State Management 🧠

- This project uses React's built-in **Context API** for state management. This approach helps to avoid prop drilling and provides a clean way to manage and share data, such as the blog posts and search query, across the component tree. Also, a custom usePosts hook is used to consume the context, making the state accessible from any component without needing to pass props down manually.

---

### Technologies Used ⚙

- **React**: The javaScript library for building the user interface.

- **JavaScript**: The programming language used throughout the project.

- **PURE CSS**: For styling the user interface.

---

### How to Run the Project

1.  **Clone the repository**:

    ```bash
    git clone https://github.com/Mhmd-abi-hachem/atomic-blog-reactjs.git
    ```

2.  **Install the dependencies**:

    ```bash
    npm install
    ```

3.  **Start the development server**:
    ```bash
    npm start
    ```
