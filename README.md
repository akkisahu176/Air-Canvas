# Air Canvas

Air Canvas is an interactive virtual painting application that allows users to draw on a canvas by waving a colored object in front of their webcam. The application uses computer vision techniques to detect the color and track the movement of the object, allowing the user to create drawings in real-time.

## Features

- **Real-Time Drawing:** Draw on a virtual canvas by simply moving a colored object in front of your webcam.
- **Color Detection:** Adjust color detection using trackbars for fine-tuning.
- **Multiple Colors:** Supports drawing with four different colors - Blue, Green, Red, and Yellow.
- **Clear Option:** Quickly clear the canvas using the "Clear All" button.

## Requirements

- Python 3.x
- OpenCV
- NumPy

You can install the required libraries using the following command:

```bash
pip install opencv-python numpy
```

## How It Works

1. **Color Detection:** The application uses the HSV color space to detect the color of the object. You can adjust the upper and lower bounds of the Hue, Saturation, and Value (HSV) to fine-tune the color detection.
  
2. **Drawing on Canvas:** Once the color is detected, the application tracks the movement of the object and allows you to draw on a virtual canvas.

3. **UI Controls:** The application features a simple UI with buttons for selecting colors and clearing the canvas. The UI and canvas are displayed in separate windows.

## Usage

1. **Run the Application:**
   ```bash
   python air_canvas.py
   ```

2. **Adjust Color Detection:** Use the trackbars to adjust the upper and lower HSV values for better color detection.

3. **Draw:** Move the colored object in front of your webcam to start drawing on the canvas. You can switch between Blue, Green, Red, and Yellow colors using the buttons in the UI.

4. **Clear Canvas:** Click the "Clear All" button to clear the canvas.

5. **Exit:** Press the 'q' key to exit the application.

## Code Overview

The core functionalities of the application include:

- **Color Detection:** Using trackbars to adjust HSV values for color detection.
- **Drawing Logic:** Tracking the colored object and drawing on the canvas based on its movement.
- **UI:** Creating a simple user interface with buttons for color selection and clearing the canvas.

## Demo

![Demo Image](https://github.com/akkisahu176/Air-Canvas/blob/773da0fffee14a230f1d2333b16891adbb59d0bc/Air%20Canvas%20Demo.png)  
_A screenshot of the Air Canvas in action._

## Future Enhancements

- Improve color detection under varying lighting conditions.
- Add more color options and brush sizes.
- Implement shape drawing (lines, rectangles, circles).



---

Make sure to update the `Demo Image` section with an actual path to the image if you include a demo screenshot.
