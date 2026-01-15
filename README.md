# Calculator (React-Vite)

## Description
This is a **modern, responsive calculator** built with **React 18** and **Vite**. It supports basic arithmetic operations and provides a clean, intuitive user interface that works well on both **desktop and mobile devices**.  

The project demonstrates best practices in React development, including **state management with `useReducer`**, **component-based architecture**, and **responsive CSS grid design**.

---

## Features
- Basic arithmetic: Addition, subtraction, multiplication, division
- Clear (`AC`) and delete (`DEL`) functionality
- Floating point support
- Responsive design: Works on mobile, tablet, and desktop
- Stable output area to prevent layout jumping
- Modern gradient styling for a visually appealing UI

---

## Technologies Used
- [React 18](https://reactjs.org/) – Front-end UI library
- [Vite](https://vitejs.dev/) – Fast development build tool
- JavaScript / JSX – Component-based architecture
- CSS Grid & Flexbox – Responsive layout

---

## Installation

1. **Clone the repository**

```bash
git clone <repository-url>
cd calculator-vite
````

2. **Install dependencies**

```bash
npm install
```

3. **Run the development server**

```bash
npm run dev
```

4. **Open the app in your browser**

By default: [http://localhost:5173](http://localhost:5173)

---

## Project Structure

```
calculator-vite/
├── index.html         # HTML entry point
├── package.json       # Project metadata & scripts
├── src/
│   ├── main.jsx       # React entry point
│   ├── App.jsx        # Main calculator component
│   ├── actions.js     # Shared constants for reducer
│   ├── components/    # DigitButton, OperationButton
│   └── index.css      # Styling (responsive & gradient background)
└── vite.config.js     # Vite configuration
```

---

## Usage

* Click numeric buttons to input numbers
* Use operation buttons (`+`, `−`, `×`, `÷`) to perform calculations
* Press `AC` to clear all
* Press `DEL` to delete the last digit
* Press `=` to evaluate the expression

---

## Screenshots

*(Add screenshots here for desktop, tablet, and mobile if desired)*

---

## Optional Enhancements

* Add **keyboard support** for typing numbers and operations
* Implement **scientific calculator functions**
* Dark/light theme toggle
* Smooth button animations

---

## License

This project is **open-source** and free to use for personal or educational purposes.
