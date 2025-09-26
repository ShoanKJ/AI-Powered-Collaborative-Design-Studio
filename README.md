# AI-Powered Collaborative Design Studio

## 💡 Project Concept

The **AI-Powered Collaborative Design Studio** is a foundational, web-based drawing application built from the ground up to support limitless creative brainstorming. It currently serves as an ultra-lightweight, single-file prototype focused on a fully functional **infinite canvas** experience.

The core mission of this project is to create an open-source platform that will eventually integrate advanced features, including **real-time multiplayer collaboration** and various **AI-driven design assistance tools**.

---

## 🔗 Live Application

Experience the infinite canvas directly in your browser!

**[Launch AI-Powered Collaborative Design Studio](https://shoankj.github.io/AI-Powered-Collaborative-Design-Studio)**

---

## ✨ Core Feature Breakdown

The current version of the studio is implemented entirely in vanilla JavaScript and focuses on robust, low-level canvas manipulation to create a non-destructive object model.

### **The Infinite Canvas System**

* **Viewport Independence:** The canvas is not limited by the screen size. All drawing operations are mapped to a virtual, unbounded **World Coordinate System**.
* **Seamless Navigation:** Achieves the illusion of infinite space through intelligent application of **CSS Transforms** (`translate` and `scale`) to the canvas element itself, ensuring smooth performance even at extreme zoom levels.
* **Pan & Zoom:** Navigate the entire space effortlessly using the mouse wheel (Zoom) or the dedicated **Pan (Move) tool** (or holding the **Spacebar**).

### **Drawing & Object Model**

* **Vector-Like Editing:** Unlike traditional pixel-based drawing, every shape (rectangles, lines, text, and even brush strokes) is stored as a distinct **JavaScript Object** with properties (coordinates, color, size).
* **Non-Destructive Manipulation:** Use the **Select (V)** tool to **move or reposition** any existing object anywhere on the canvas without altering the objects underneath it.
* **Robust History:** Implements a full state-based history system, enabling limitless **Undo (Ctrl/Cmd + Z)** and **Redo (Ctrl/Cmd + Y)** for all drawing and object manipulation actions.

### **Tool Set & Utility**

| Tool | Shortcut | Description |
| :--- | :--- | :--- |
| **Brush** | `B` | Freehand drawing with adjustable stroke width and color. |
| **Eraser** | `E` | Non-destructive tool that uses `destination-out` composite operation to erase content. |
| **Shapes** | `L, R, C` | Tools for drawing perfect Lines, Rectangles, and Circles. |
| **Text** | `T` | Place interactive text input fields on the canvas (stored as objects). |
| **Layers** | N/A | Basic organizational structure to manage groups of objects. |
| **Snapping Grid** | N/A | Toggle a visible grid that snaps all new drawing points for precise alignment. |

---

## 🛠️ Technology Stack

This project is intentionally built using the absolute minimum set of technologies to maximize compatibility, performance, and simplicity.

* **HTML5:** Structure and Canvas Element.
* **CSS3:** Styling and crucial performance-boosting canvas transformations.
* **Vanilla JavaScript (ES6+):** All application logic, state management, and custom `DrawingApp` class.
* **Canvas API:** Used for high-performance rendering of shapes and paths.

---

## 🚀 Getting Started (Local Development)

The studio is designed for zero-setup local use.

1.  **Clone the Repository:**
    ```bash
    git clone
