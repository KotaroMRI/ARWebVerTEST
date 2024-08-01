# WebAR Project

## Overview
This project demonstrates a WebAR application using A-Frame and AR.js. The application features a 3D model that appears when a specific marker is detected. Users can adjust the model's position using on-screen controls, and the model will stay fixed at its last known position even when the marker is no longer visible.

## Setup

1. **Clone this repository:**
    ```bash
    git clone https://github.com/your-username/your-repo-name.git
    ```

2. **Navigate to the project directory:**
    ```bash
    cd ARWebVerTEST
    ```

3. **Open `index.html` in a web browser to view the WebAR application.**

## Files

- `index.html`: The main HTML file containing the WebAR setup and position adjustment controls.
- `assets/asset.glb`: The 3D model used in the application.
- `assets/Marker.patt`: The pattern marker used to trigger the AR model.

## Notes

- Ensure that the `asset.glb` and `Marker.patt` files are correctly placed in the `assets` directory.
- The application is designed to work offline without the need for a local server.
