Rep Counter is a gym tracking tool powered by AI that utilizes pose estimation to count repetitions during exercises. It makes use of various technologies such as MediaPipe, OpenCV, Python, NumPy, and Trigonometry. By analyzing the webcam feed, the system detects different poses, extracts joint coordinates, calculates joint angles, and provides real-time feedback for counting reps.

To install Rep Counter, you can follow these steps:

1. Clone the repository by running the following command in your terminal:
   ```
   git clone https://github.com/hrharshit/Rep_counter.git
   ```

2. Ensure you have Python and pip installed on your system.

3. Install the required dependencies by navigating to the project directory and running the following command:
   ```
   pip install -r requirements.txt
   ```

To use Rep Counter:

1. Connect a webcam to your computer.

2. Launch the Rep Counter application by running the following command in your terminal:
   ```
   python rep_counter.py
   ```

3. The Rep Counter will start processing the webcam feed.

4. Perform exercises in front of the webcam, and the Rep Counter will count your reps based on detected poses and joint movements.

5. Monitor the Rep Counter's output on the screen to keep track of your performance.

Rep Counter can be customized according to specific requirements:

1. Modify the rep counting algorithm in `rep_counter.ipynb` to suit different exercises.

2. Adjust the pose estimation parameters in `rep_counter.ipynb` to optimize accuracy or performance.

3. Customize the rendering of pose estimation results using OpenCV in `rep_counter.ipynb`.

Acknowledgments:

This project draws inspiration from the AI and computer vision technologies provided by MediaPipe and the open-source community supporting Python, OpenCV, NumPy, and Trigonometry.

Contributions to the project are welcome! If you encounter any issues or have ideas for improvements, please submit a pull request or open an issue on the GitHub repository.

Author: Harshit Raj - www.github.com/hrharshit/

References:

- MediaPipe documentation: https://developers.google.com/mediapipe/
- OpenCV documentation: https://docs.opencv.org/4.x/d1/dfb/intro.html
