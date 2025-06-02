# Interactive Mathematical Object Studies

This repository contains a collection of interactive HTML-based examples designed for studying and visualizing 2D and 3D abstract mathematical objects. Each file provides a hands-on way to explore different concepts.

## File Descriptions

This repository includes the following interactive HTML examples:

*   **`cartesia-2d.html`**:
    *   **Description**: An interactive 2D Cartesian plane.
    *   **Features**:
        *   Click on grid cells to display their (x, y) coordinates.
        *   Drag the origin (0,0) to any position on the grid, and all coordinates will be recalculated dynamically.
        *   Visual distinction for axes, origin, and clicked points.

*   **`cartesia-3d.html`**:
    *   **Description**: An interactive 3D Cartesian coordinate system.
    *   **Features**:
        *   Input X, Y, and Z coordinates to mark points in a 3D space.
        *   Rotate the 3D view using mouse drag.
        *   Zoom in/out using the mouse wheel.
        *   Displays a list of marked points.
        *   Color-coded axes (X: Red, Y: Green, Z: Blue).

*   **`cartesia-2d-trigonometria.html`**:
    *   **Description**: An interactive 2D Cartesian plane with a focus on trigonometry.
    *   **Features**:
        *   Click on any point in the 2D grid (except the origin).
        *   Displays Cartesian coordinates (x,y) and polar coordinates (radius, angle).
        *   Shows trigonometric values: sine, cosine, and tangent for the selected point relative to the origin.
        *   Visualizes the angle, radius, and projections on the X and Y axes directly on the grid.
        *   Includes a separate interactive unit circle diagram that mirrors the selected point's trigonometric properties.

*   **`cartesia-3d-trigonometria.html`**:
    *   **Description**: An interactive 3D Cartesian system that also explores trigonometric relationships.
    *   **Features**:
        *   Mark points in 3D space by inputting X, Y, Z coordinates.
        *   Rotate the 3D view and zoom.
        *   Select a marked point to view its trigonometric relationships.
        *   Choose to project the relationships onto the XY, XZ, or YZ plane.
        *   Displays values for sine, cosine, tangent, and angles based on the selected plane of projection.
        *   Visually represents the vector, its projections, and angles in the 3D space.

*   **`chatgpt5.html`**:
    *   **Description**: An interactive isometric grid viewer with dynamic elements. Despite its name, it does not appear to have direct functionality related to ChatGPT.
    *   **Features**:
        *   Displays a pannable and zoomable isometric grid.
        *   Features floating images on certain grid cells that animate and can be clicked to expand.
        *   Clicking on grid cells highlights them.
        *   The user can interact by dragging to pan the view and using the mouse wheel to zoom.

*   **`claude.html`**:
    *   **Description**: An interactive 3D isometric grid scenario, styled similarly to tactical RPGs like Final Fantasy Tactics. The filename does not directly indicate its content.
    *   **Features**:
        *   Presents a 3D grid of tiles.
        *   Users can click on a tile to select it, which also highlights its corresponding row and column.
        *   Controls to rotate the scene, change the viewing inclination, and zoom.
        *   Keyboard shortcuts for rotation.
        *   Displays current selection, rotation, inclination, and zoom level.

## How to Use

To use these interactive examples:

1.  Clone or download this repository to your local machine.
2.  Navigate to the repository's directory.
3.  Open any of the `.html` files directly in a modern web browser (such as Chrome, Firefox, Safari, or Edge).

No special setup or server is required as these are client-side examples running entirely in the browser.

## Contributing & Future Enhancements

Contributions to this collection are welcome! If you have ideas for new interactive examples, improvements to existing ones, or bug fixes, please feel free to:

1.  Fork the repository.
2.  Create a new branch for your feature or fix.
3.  Make your changes.
4.  Submit a pull request.

Some potential areas for future enhancements could include:

*   More complex geometric shapes and transformations.
*   Interactive examples for other mathematical concepts (e.g., vectors, matrices, calculus).
*   Improved UI/UX and customizability for the existing examples.
*   Adding more detailed explanations or educational content alongside the interactive elements.
