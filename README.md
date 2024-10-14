
# Invisibility Cloak Using OpenCV

This project creates an "invisibility cloak" effect by capturing the background and mapping any blue-colored object that appears in the frame to blend it with the background. The result is an illusion where the object appears invisible.

## How It Works
The project uses the following steps:
1. **Capture Background**: Before the user appears in the frame, the background is captured and stored.
2. **Detect Blue Color**: Using color detection, the blue color (which acts as the "cloak") is identified in the video feed.
3. **Replace Blue with Background**: The blue parts of the frame are replaced with the previously captured background, creating an invisibility effect.

## Technologies Used
- **Python 3.x**: Ensure you have the latest version of Python installed.
- **OpenCV**: For video processing.
- **NumPy**: For handling image arrays.

## Setup and Installation

### Prerequisites
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/invisibility-cloak.git
   ```
2. Install **Python 3.x** (latest version).

3. Install the required dependencies:
   ```bash
   pip install opencv-python
   pip install numpy
   ```

### Running the Project
1. Ensure you have a working webcam.
2. Run the Python script:
   ```bash
   python invisibility_cloak.py
   ```

3. Make sure to wear a blue-colored cloth to see the invisibility effect!

## Contribution
Feel free to fork this repository, submit pull requests, and report any issues or suggestions.

## License
This project is licensed under the MIT License.
