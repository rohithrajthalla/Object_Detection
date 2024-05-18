**Object Detection with Plug Control**

**Overview**

This project implements a real-time object detection system using the YOLOv5 model to control a smart plug. It captures video from a webcam, identifies the number of people in the frame, and controls a smart plug accordingly—turning it on when people are present and off when they are not. Utilizing a Jetson Nano, this setup is particularly useful for energy management and automated systems in smart homes or offices.

**Features**

- **Real-time Object Detection:** Utilizes the YOLOv5 model to detect people in video frames, leveraging the processing power of the Jetson Nano.
- **Smart Plug Control:** Automates a smart plug’s operation based on the presence of people, enhancing energy efficiency.
- **GPU/CPU Compatibility:** Optimized for the Jetson Nano; checks and utilizes GPU if available; otherwise, it falls back on CPU for processing.
- **Flask Integration:** A Flask server is set up to facilitate the real-time streaming of the video feed with detected results.
- **Interactive Video Stream:** The system streams the video with an overlay of detection results and the count of detected people.

**Installation**

Clone the repository and set up the environment to run the project on a Jetson Nano.

```bash
# Clone the repository
git clone https://github.com/rohithrajthalla/Object_Detection.git

# Navigate to the project directory
cd smart-object-detection

# Install dependencies
pip install -r requirements.txt 
```

**Video Demos**

•	**CPU Usage Demo:** [Watch CPU Demo](https://youtu.be/kkErkrrjcjI) 

•	**GPU Usage Demo:** [Watch GPU Demo](https://youtu.be/pVOZdgl-qto) 

**Usage**

To run the project, ensure your Jetson Nano is set up correctly, then start the Flask server and open the web interface.

```bash
# Start the Flask server
flask run
```

**Credits**

•	[Havish Vakkalanka](https://github.com/havish-vakkalanka) **:** Co-developer of the project.

•	Kaushik Manjunatha **:** Co-developer of the project.