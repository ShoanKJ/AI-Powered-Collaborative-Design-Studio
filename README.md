# AI-Powered Collaborative Design Studio

A single-file, web-based drawing and design application built using pure **HTML, CSS, and vanilla JavaScript**, serving as an interactive canvas for rapid prototyping, brainstorming, and collaborative design sessions.

While the current version focuses on core drawing and canvas features, the architecture is designed for future integration of **AI-powered assistance** and **real-time collaboration**.

---

## 🔗 Live Application

The "AI-Powered Collaborative Design Studio" is currently hosted and accessible via **GitHub Pages**:

**[Launch Studio](https://shoankj.github.io/AI-Powered-Collaborative-Design-Studio)**

---

## ✨ Core Features

This application implements a fully functional infinite canvas built on a simple object model, enabling non-destructive editing and manipulation of drawn elements.

* **Infinite Canvas:** Provides a virtually limitless drawing space with seamless panning and zooming.
* **Essential Toolkit:** Includes core design tools: **Brush, Eraser, Line, Rectangle, Circle, Text,** and **Arrow**.
* **Object Manipulation:** Use the **Select (V)** tool to move, reposition, and manipulate existing drawing objects.
* **View Controls:** Navigate effortlessly using **Pan (Spacebar)** and **Zoom (Mouse Wheel)**.
* **History Management:** Robust **Undo/Redo (Ctrl/Cmd + Z/Y)** functionality for all design changes.
* **Layering System:** Basic layer management for organizing complex designs.
* **Snapping Grid:** Toggle a grid overlay that assists with precise object placement.

---

## 🚀 Getting Started (Local Development)

Since this project is a single-file application, it requires no server or build steps for local use.

1.  **Clone the Repository:**
    ```bash
    git clone [https://github.com/ShoanKJ/AI-Powered-Collaborative-Design-Studio](https://github.com/ShoanKJ/AI-Powered-Collaborative-Design-Studio)
    ```
2.  **Launch:** Simply **drag the `index.html` file into any modern web browser** (Chrome, Firefox, Safari, etc.) or double-click the file to open it.

---

## 🚧 Future Development Roadmap

The current version lays the foundation for advanced features. Planned additions include:

* **AI Integration:** Implement logic for features like "smart cleanup," "auto-suggested connections," or "design pattern recognition."
* **Real-time Collaboration:** Integrate a backend service (e.g., Firebase, WebSocket) to enable multiple users to interact on the same canvas concurrently.
* **Export Functionality:** Full implementation of **PNG** and **SVG export** (currently placeholders).
* **Advanced Editing:** Tools for manipulating text content, resizing shapes, and advanced object transformation.
