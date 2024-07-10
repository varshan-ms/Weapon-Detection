
---

# Weapon Detection Project

## Overview

The Weapon Detection project aims to develop a robust system for detecting weapons in images and videos using the YOLO (You Only Look Once) object detection algorithm. This system is designed to enhance security measures by providing real-time weapon detection capabilities.

## Features

- **Real-Time Detection:** Utilizes the YOLO algorithm to detect weapons in real-time.
- **High Accuracy:** Capable of accurately identifying various types of weapons.
- **User-Friendly Interface:** Simple interface for easy interaction and monitoring.

## Technologies & Tools Used

- **Programming Language:** Python
- **Libraries:** OpenCV, TensorFlow, Keras, YOLO
- **Development Environment:** PyCharm

## Installation

To run this project locally, follow these steps:

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/varshan-ms/Weapon-Detection.git
   ```

2. **Create and Activate Virtual Environment (optional but recommended):**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
   ```

3. **Install Dependencies:**
   ```bash
   pip install -r requirements.txt
   ```
   
   Or manually install the required packages:
   ```bash
   pip install opencv-python
   pip install tensorflow
   pip install keras
   pip install yolo
   ```

4. **Download YOLO Weights:**
   Download the pre-trained YOLO weights from the official YOLO website or another reliable source and place them in the `yolo/weights` directory.

5. **Run the Application:**
   ```bash
   python main.py
   ```

## Usage

1. **Launching the Application:** Once the application is running, a window will appear where you can select images or videos for weapon detection.
2. **Selecting Media:** Choose an image or video file for analysis. The system will process and display the results with detected weapons highlighted.
3. **Real-Time Monitoring:** For real-time detection, use a webcam or connected camera to monitor the feed for weapons.

## Project Structure

```
weapon-detection/
├── yolo/
│   ├── config/                 # YOLO configuration files
│   ├── weights/                # YOLO pre-trained weights
├── data/                       # Sample images and videos for testing
├── src/
│   ├── detection.py            # Weapon detection logic
│   ├── preprocess.py           # Data preprocessing scripts
│   ├── postprocess.py          # Post-processing scripts
│   └── gui.py                  # GUI implementation using Tkinter
├── main.py                     # Main application file
├── requirements.txt            # Project dependencies
└── README.md                   # Project README file

```
![alert](https://github.com/varshan-ms/Weapon-Detection/assets/170520754/4f940362-a103-43e1-9ed2-555d990a3e14)

![lena_invert](https://github.com/varshan-ms/Weapon-Detection/assets/170520754/1f8335a8-63d6-4776-a1a9-2d8c6433022e)



## Contributing

Contributions are welcome! Please fork this repository and submit a pull request for any improvements or bug fixes.

## Contact

For any inquiries or questions, feel free to reach out:

- Email: msvarshan07@gmail.com
- LinkedIn: [msvarshan](https://www.linkedin.com/in/msvarshan)

---

