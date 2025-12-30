# 🧬 The Prototype Chapter Visualizer

An interactive, deep-dive learning tool designed to visualize the core mechanism of JavaScript: **The Prototype**. This application breaks down the journey from raw object delegation to modern class syntax with real-time visual feedback.

## 🚀 Overview

JavaScript's object-oriented nature is powered by **Prototypal Inheritance**. Instead of static class blueprints, objects inherit directly from other objects via a live link called the `[[Prototype]]`. This visualizer allows you to witness this "live link" in action through four interactive chapters.

## 📚 Chapters Covered

1.  **Part 1: The Foundation** 🧱
    *   Manual prototype chain creation using `Object.create()`.
    *   Visualizing property lookup through the "Grandparent," "Parent," and "Child" hierarchy.
2.  **Part 2: Constructors & `new`** 🏗️
    *   The transition to the "Classical" pattern.
    *   Step-by-step execution of the `new` keyword (Creation, Linking, Execution, Returning).
3.  **Part 3: Prototypal Inheritance** ⛓️
    *   Advanced linking between constructor prototypes.
    *   Chaining instance properties using `.call(this, ...)` and fixing the `.constructor` reference.
4.  **Part 4: The `class` Syntax** ✨
    *   Modern ES6 "syntactic sugar."
    *   Visual proof that `extends` and `super()` are built entirely on top of the prototype system.

## 🕹️ Interactive Zones

*   **Code Execution** 💻: Watch the logic unfold line-by-line with synchronized highlighting.
*   **Live Object Model** ⚪: Dynamic white boxes representing "Instances" and "Prototypes" in memory.
*   **Narrator (Drag Elsewhere)** 🗣️: A floating, draggable, and resizable guide providing conceptual context from the original documentation.
*   **DevTools Console** 📟: A replica of the browser console showing property lookups, equality checks, and **literal function definitions** (e.g., `ƒ drive() { ... }`).
*   **Visual Pointers** 🏹: Smooth, wavy SVG arrows that track objects in real-time, even during window resizing or zooming.

## 🛠️ Technical Highlights

*   **Object Inspector**: A custom-built recursive tree renderer for the console to display the hidden `[[Prototype]]` chain.
*   **Vanilla Implementation**: Built with pure JavaScript, CSS, and HTML, utilizing **PrismJS** for syntax highlighting.
*   **Responsive Design**: Ensures usability across various screen sizes and devices.

## 📖 How to Use

1.  Select a **Chapter Button** at the top.
2.  Follow the **Line Highlighter** in the code box.
3.  Read the **Narrator** for the conceptual "Why."
4.  Inspect the **Live Object Model** to see properties being added and linked.
5.  Check the **DevTools Console** for final execution values and prototype comparisons.

Click https://manjilj.github.io/prototype-v/ to explore the Prototype Chapter Visualizer!

---
*Understanding prototypes is understanding the true nature of JavaScript.* 🧪
