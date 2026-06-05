# CGI Fundamentals

A collection of educational code snippets exploring the basics of Computer Graphics Interface (CGI) using HTML5 Canvas and JavaScript. This repository demonstrates fundamental computer graphics algorithms and techniques through interactive visual examples.

## 📋 Overview

This project is designed to help beginners understand how CGI works by implementing various graphics algorithms from scratch. Each file demonstrates a specific concept with a complete, working example that can be opened directly in a web browser.

## 🎨 Projects Included

### 1. **Fibonacci Drawing** (`fibonacciDrawing.html`)
Visualizes the Fibonacci sequence as a geometric pattern.

**Features:**
- Generates Fibonacci numbers up to a specified limit
- Draws dots around a rectangle's perimeter
- Creates connecting lines between dots based on Fibonacci sequence distances
- Demonstrates sequence generation and coordinate mathematics

**Concepts:**
- Sequence generation algorithms
- Canvas coordinate systems
- Iterative drawing patterns

---

### 2. **Fractal Tree** (`fractalTree.html`)
Renders a recursive fractal tree structure using geometric transformations.

**Features:**
- Recursive branch generation with controlled depth
- 2D rotation transformations using trigonometric functions
- Creates a natural-looking tree pattern through mathematical recursion
- Variable depth control for complexity adjustment

**Concepts:**
- Recursive algorithms
- 2D rotation matrices and transformations
- Trigonometric calculations
- Fractal geometry

---

### 3. **Bézier Curve & B-Spline** (`bezierCurve.html`)
Implements two fundamental curve algorithms used in computer graphics.

**Features:**
- **De Casteljau Algorithm:** Iterative implementation of Bézier curve calculation
- **B-Spline Curve:** Cubic B-spline implementation for smooth interpolation
- Interactive visualization with 6 control points
- Color-coded output:
  - 🔵 Blue: Bézier curve
  - 🔴 Red: B-spline curve
  - 🟢 Green: Control polygon (connecting vertices)

**Concepts:**
- Parametric curve equations
- Bézier curve mathematics
- B-spline basis functions
- Iterative point calculation methods

---

## 🚀 Getting Started

### Prerequisites
- Any modern web browser (Chrome, Firefox, Safari, Edge)
- No additional dependencies or installations required

### Running the Examples

1. Clone the repository:
   ```bash
   git clone https://github.com/Yehor40in/cgi-fundamentals.git
   ```

2. Open any HTML file directly in your browser:
   - Navigate to the repository folder
   - Double-click on any `.html` file, or
   - Use a local server (recommended):
     ```bash
     python -m http.server 8000
     # Then visit http://localhost:8000 in your browser
     ```

## 📚 Concepts Covered

### Fundamental CGI Techniques
- **Canvas Rendering:** Using HTML5 Canvas API for 2D graphics
- **Coordinate Geometry:** Working with 2D points and vectors
- **Transformations:** Rotation, translation, and scaling
- **Parametric Curves:** Bézier and B-spline mathematics
- **Recursion:** Implementing fractal patterns
- **Sequence Algorithms:** Generating mathematical sequences

### Mathematics
- Trigonometric functions (sin, cos)
- Distance calculations
- Parametric equations
- Rotation matrices
- Interpolation techniques

## 💻 Code Structure

Each HTML file follows a similar structure:

```javascript
// Object-oriented design with setup and drawing methods
let Figure = function(parameters) {
    let canvas, ctx;  // Canvas context
    
    this.setup = function() {
        // Initialize canvas
    }
    
    this.draw = function() {
        // Drawing logic
    }
}

// Instantiate and execute
window.onload = function() {
    let figure = new Figure(params);
    figure.setup();
    figure.draw();
}
```

## 🎓 Educational Value

This repository is ideal for:
- Students learning computer graphics fundamentals
- Developers new to canvas-based visualization
- Anyone interested in algorithm implementation
- Visual learners who benefit from seeing code produce graphics

## 🔧 Technologies Used

- **HTML5:** Page structure and canvas element
- **CSS:** Basic styling
- **JavaScript (Vanilla):** All graphics algorithms and calculations
- **Canvas API:** 2D drawing context

## 📝 Notes

- All files are self-contained with no external dependencies
- Code is written for clarity and educational purposes rather than optimization
- Comments in Ukrainian reflect the original educational context
- Each implementation prioritizes understanding over performance

## 🤝 Contributing

This is an educational project. If you have suggestions for improvements, additional algorithms, or better explanations, feel free to open an issue or submit a pull request.

## 📄 License

This repository is shared for educational purposes. Feel free to use, modify, and learn from this code.

## 📧 Contact

For questions or suggestions about the code, please open an issue on GitHub.

---

**Happy Learning! 🎨📐**
