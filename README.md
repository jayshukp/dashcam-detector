# Dashcam Detector

This is a computer vision application developed using the Python programming language and the OpenCV library. It is designed to analyze video footage captured by a dash cam and detect various objects or patterns of interest on the road.

## How It Works

- The application employs cascade XML files, which are pre-trained models in the form of a hierarchical structure of classifiers. These XML files contain the necessary information to detect specific objects, specifically pedestrians and vehicles from all around the world.
- Afterwards, integrating the OpenCV library, the software reads the video input frame by frame. For each frame, it applies the cascade classifiers defined in the cascade XML files. The classifiers work by scanning the image at multiple scales and locations, searching for matches with the patterns they were trained to recognize, and places red and blue colored rectangles for pedestrians and vehicles, respectively.

## How to Use It Yourself

If you want to play with the software and use your own dashcam footage for object detection, follow these steps:

1. Firstly, clone the repository to your local machine via a folder and make sure you have at least Python 3 installed.
2. Secondly, place your dashcam footage of choice in the respective folder and name it with a `.mp4` extension.
3. Access your clone in your IDE of choice and locate the `Car-Pedestrian_Detector.py` file.
4. In line 6, adjust the line `vid_file = cv2.VideoCapture('footage.mp4')` where you input your specified video file in place of `'footage.mp4'`.
5. Finally, access the terminal window and run `python3 Car_and_Pedestrian_Detector.py` or `python Car_and_Pedestrian_Detector.py` to run the dashcam footage.

For any questions or issues regarding the dashcam detector, feel free to contact the project maintainer at [jaypandrangi@gmail.com](mailto:jaypandrangi@gmail.com).

Thank you for your interest in the project, and enjoy using the dashcam detector!

## 

![Screenshot 2023-06-25 at 11 56 01 PM](https://github.com/jayshukp/dashcam-detector/assets/137319067/3d5164e5-8668-47a2-aecc-19211460e614)
