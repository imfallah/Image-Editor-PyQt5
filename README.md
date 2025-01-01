# Image Editor with PyQt5 📸🐍

<picture> <img align="left" src="https://github.com/imfallah/Image-Editor-PyQt5/blob/main/public/img-edi.png" width=500></picture>


## Overview🔗
This project is a feature-rich **Image Editor** built with PyQt5. It provides an intuitive graphical user interface (GUI) for editing images with various filters, adjustments, and tools. Whether you're a developer or a casual user, this application is designed to make image editing simple and enjoyable.

## Features❣⚡

### 1. Splash Screen
- Displays a visually appealing splash screen with a progress bar while the application loads.
- Includes drag-and-drop functionality to move the window.

### 2. File Selection
- A modern file dialog for selecting image files.
- Supports multiple formats: `.jpg`, `.png`, `.jpeg`, `.ico`.
- Allows selecting multiple files at once.

### 3. Main Editor
- **Image Display**: Shows the selected image with zoom and pan support.
- **Filters**: Apply various filters to enhance or stylize images.
- **Adjustments**: Modify brightness, contrast, saturation, and other image properties.
- **Save Functionality**: Save edited images in the desired format.
- **Zoom Functionality**: Zoom in/out using the mouse wheel.
- **Flip and Rotate**: Easily flip or rotate images.

### 4. Modular Design
- **Filter Frame**: Separate UI component for applying filters.
- **Adjustment Frame**: Dedicated UI for fine-tuning image properties.
- **Reusable Components**: Each feature is encapsulated for easy modification and extension.

## Requirements🥇

- Python 3.8 or later
- PyQt5
- OpenCV
- qimage2ndarray

To install the dependencies, run:
```bash
pip install PyQt5 opencv-python qimage2ndarray
```

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/imfallah/pyqt5-image-editor.git
   cd pyqt5-image-editor
   ```

2. Install the required dependencies (see above).

3. Run the application:
   ```bash
   python main.py
   ```

## File Structure🌳
```
pyqt5-image-editor/
├── main.py             # Entry point of the application
├── ui/
│   ├── startup.ui    # UI for the file selection window
│   └── main.ui       # UI for the main editor window
├── images/            # Directory for sample images (optional)
├── widgets.py        # Custom widgets and utility classes
├── index.py          # UI components for the splash screen
└── README.md         # Project documentation
```

## Usage🔗👀

1. Launch the application using `python main.py`.
2. Use the splash screen to track the loading process.
3. Select images through the file dialog.
4. Edit images in the main editor window:
   - Apply filters using the filter frame.
   - Adjust brightness, contrast, and more using the adjustment frame.
5. Save your work in the desired format.

## Future Enhancements🏆
- Add more filters and adjustment options.
- Improve the zoom and pan experience.
- Introduce undo/redo functionality.
- Support for batch processing of images.

## Contributing🙌🏽
Contributions are welcome! If you have ideas for new features or improvements, feel free to fork the repository and submit a pull request.

## ScreenShot📸

<img src="https://github.com/imfallah/Image-Editor-PyQt5/blob/main/public/main_screen.png" width="500" height="500"><br><br>
