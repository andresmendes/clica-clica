
# Clica-clica

## Description

**Clica-clica** is a simple web-based tool designed for marking points on an image and exporting these points as CSV files. It provides basic functionality for adding, moving, and deleting points, as well as zooming and panning for better precision. This tool can be used for tasks that require mapping or organizing points on an image, such as creating coordinate maps or preparing data for further processing.

---

## Features
- **Drag-and-Drop Image Upload**: Easily upload an image by dragging and dropping it into the interface.
- **Point Management**:
  - Add points by left-clicking on the canvas.
  - Move existing points by dragging them to a new position.
  - Delete points with a right-click.
  - Add midpoints between existing points by clicking on the green markers.
- **Zoom and Pan**:
  - Use the mouse wheel to zoom in and out.
  - Middle-click and drag to pan across the canvas.
- **CSV Import and Export**:
  - Import CSV files to load points.
  - Export points as a CSV file.
- **Responsive Interface**:
  - Automatically adjusts the canvas size to fit the browser window.
- **Help Modal**:
  - A built-in help modal explains the tool’s features and usage.

---

## Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Edge, or Safari).

### Running Locally
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/clica-clica.git
   cd clica-clica
   ```
2. Open the `index.html` file in your browser.

---

## How to Use

### Uploading an Image
1. Drag and drop an image onto the canvas or the "Drag and Drop an Image Here" area.
2. The image will automatically load into the canvas, and the tools will be activated.

### Managing Points
- **Add Points**: Left-click on the canvas to create a new point.
- **Move Points**: Drag an existing point to move it.
- **Delete Points**: Right-click on a point to remove it.
- **Add Midpoints**: Click on green midpoint markers (between two points) to create a new point.

### Zoom and Pan
- Scroll with the mouse wheel to zoom in or out.
- Press and hold the middle mouse button to pan across the canvas.

### Importing and Exporting Points
- **Import CSV**: Click the "Load CSV" button and select a `.csv` file (format: `x,y` per line).
- **Export CSV**: After creating or editing points, click "Export CSV" to save them as a `.csv` file.

---

## File Format

### CSV Import/Export
- Each line in the CSV file represents a point in the format:
  ```
  x,y
  ```
- Example:
  ```
  100,150
  200,300
  ```

---

## Contributing
Contributions are welcome! If you'd like to contribute:
1. Fork the repository.
2. Create a new branch for your feature or fix.
3. Submit a pull request.

