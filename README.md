# Air Canvas

Air Canvas is a computer vision-based drawing application that allows you to draw on a virtual canvas using hand gestures. This project uses OpenCV, MediaPipe, and NumPy to track hand movements and draw on the screen.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)

## Features

- Real-time hand tracking using MediaPipe.
- Draw on a virtual canvas using hand gestures.
- Switch between different colors (Blue, Green, Red, Yellow).
- Clear the canvas with a hand gesture.

## Installation

1. **Clone the repository:**

    ```bash
    git clone https://github.com/chandnii96/air-canvas.git
    cd air-canvas
    ```

2. **Create a virtual environment and activate it:**

    ```bash
    python -m venv venv
    # Windows
    venv\Scripts\activate
    # macOS/Linux
    source venv/bin/activate
    ```

3. **Install the required packages:**

    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. **Run the application:**

    ```bash
    python paint_app.py
    ```

2. **Use your hand to draw on the virtual canvas:**

    - Raise your index finger to draw.
    - Use the buttons at the top of the window to switch colors or clear the canvas.
    - To clear the canvas, move your index finger to the "CLEAR" button.
    - To change colors, move your index finger to the respective color button.

3. **Press 'q' to quit the application.**

