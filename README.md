# Abnormal Event Detection On Pathway Using Video Surveillance System , YOLO and Flask

This repository contains code for a video surveillance system implemented using YOLO (You Only Look Once) object detection and Flask web framework. The system is capable of detecting various events such as accidents, fighting, kidnapping, and chain snatching in real-time video streams or pre-recorded videos. It also provides a web interface for viewing the surveillance dashboard and accessing the detected videos.

## Features

- Real-time object detection using YOLO.
- Event-based recording and uploading of videos to Cloudinary.
- Web interface for user authentication and viewing surveillance dashboard.
- Support for both live video streams and pre-recorded videos.
- Responsive UI for easy access from any device.

## Abstract
To enhance road safety and prevent accidents, this project focuses on developing a system to detect abnormal activities on roads in real-time. With YOLOv8, an object detection model, our approach aims to identify various irregularities such as accidents, reckless driving, and pedestrian crossings. Through a comprehensive training process and fine-tuning of the YOLOv8 model, we adapt it to the specific requirements of road safety monitoring. At the beginning of the configuration, we discuss combining Flask for web application development and Cloudinary for video storage which provides the user with user authentication, video processing, and streaming. In the end, it detects the specific objects in a video stream, records segments of the video when these objects are detected, and then uploads the recorded segments to Cloudinary


## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/your-repository.git
   ```

2. Install dependencies:

   ``` 
   pip install ultralytics cloudinary WTForms Flask Werkzeug opencv-python
   ```

3. Set up Cloudinary account and obtain API credentials.
   
4. Update the `cloudinary.config()` in `flaskapp.py` and `YOLO_video.py` with your Cloudinary API credentials.

5. Run the Flask application:

   ```bash
   python flaskapp.py
   ```

6. Access the application in your web browser at `http://localhost:5000`.

## Usage

- Log in with your username and password to access the surveillance dashboard.
- Upload a video file or provide a video stream URL.
- Monitor real-time object detection and view detected videos in the dashboard.
- Customize object detection classes and thresholds as needed.

## Model  [Link](https://drive.google.com/file/d/1j9kSzI7T8gUMLRnBlL3S1LXYimoXg9UG/view?usp=sharing) 
place it in ./best.pt


## Contributing

Contributions are welcome! If you find any bugs or have suggestions for improvement, please open an issue or submit a pull request.


## Project Document [LINK](https://github.com/vishwanathkarka/Abnormal-Event-Detection-On-Pathway/files/14969800/main.doc.pdf)

## Project PPT [LINK](https://github.com/vishwanathkarka/Abnormal-Event-Detection-On-Pathway/files/14969845/Abnoramal.Event.Detection.on.Pathway.using.Yolo.pdf)
 
## Literature survey [LINK](https://github.com/vishwanathkarka/Abnormal-Event-Detection-On-Pathway/files/14969839/Abnormal_Event_Detection_On_Pathway__Copy_.1.pdf)

[Vamshi Yadav Literature Review.pdf](https://github.com/vishwanathkarka/Abnormal-Event-Detection-On-Pathway/files/14969903/20R21A6606.Literature.Review.1.pdf)

[Sudhansh Narayan Literature Review.pdf](https://github.com/vishwanathkarka/Abnormal-Event-Detection-On-Pathway/files/14969902/20R21A6629.Literature.Review.pdf)


[Vishwanath Reddy Karka Literature Review.pdf](https://github.com/vishwanathkarka/Abnormal-Event-Detection-On-Pathway/files/14969901/21R25A6603.Literature.Review.1.pdf)


[Aarya Gouthula Literature Review.pdf](https://github.com/vishwanathkarka/Abnormal-Event-Detection-On-Pathway/files/14969900/20R21A6619.Literature.Review.2.pdf)

## License

This project is licensed under the [MIT License](LICENSE).


