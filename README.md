# FaceBlurring

This is a Python application for blurring faces in images and videos using the MediaPipe library for face detection. It also blur faces in real-time.

Installation
Clone this repository to your local machine:
bash
Copy code
git clone https://github.com/your_username/face-blur-application.git

Install the required dependencies:
Copy code
pip install -r requirements.txt

Usage
Arguments
--mode: Specifies the mode of operation. It can be one of the following:

webcam: Process frames from the webcam in real-time.
image: Process a single image file.
video: Process a video file.
--filePath: Path to the input file (image or video). Required if --mode is set to image or video.

Examples
Process an image:
css
Copy code
python face_blur.py --mode image --filePath path/to/image.jpg
Process a video:
css
Copy code
python face_blur.py --mode video --filePath path/to/video.mp4
Use webcam:
css
Copy code
python face_blur.py --mode webcam

Output
For the image mode, the processed image will be saved as output/output.png.
For the video mode, the processed video will be saved as output/output.mp4.

Acknowledgments
This project utilizes the MediaPipe library for face detection.
Inspiration for this project came from the need to anonymize faces in images and videos in real-time for privacy reasons.
