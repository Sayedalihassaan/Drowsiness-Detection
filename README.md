# Drowsiness Detection

## Overview
Drowsiness Detection is a project designed to enhance safety by identifying signs of drowsiness in individuals, such as drivers. The system leverages computer vision and machine learning to detect drowsiness in real-time and alert the user before accidents occur. This application can significantly contribute to reducing incidents caused by fatigue-related impairment.


![Drowsiness Detection Demo]([images/drowsiness-demo.png](https://kajabi-storefronts-production.kajabi-cdn.com/kajabi-storefronts-production/file-uploads/blogs/22606/images/5481e13-3da0-b8e5-f87f-a5ff1b6da72c_eyeSight_-_Driver_Monitoring_Driver_Asleep_1.jpeg))


## Features
- Real-time video analysis.
- Drowsiness detection using facial landmarks.
- Alerts for drowsy behavior to ensure user safety.

## Installation

### Prerequisites
Ensure you have the following installed:
- Python 3.7+
- OpenCV
- dlib
- NumPy

### Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/drowsiness-detection.git
   cd drowsiness-detection
   ```
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the application:
   ```bash
   python drowsiness_detection.py
   ```

## Usage
1. Ensure your webcam is connected.
2. Launch the application by running `python drowsiness_detection.py`.
3. Follow on-screen instructions to start monitoring.

## How It Works
The project utilizes:
- **Facial landmark detection:** To identify key points around the eyes and mouth.
- **Eye Aspect Ratio (EAR):** To measure blink rate and eye closure duration.
- **Real-time alerts:** Generated when drowsiness is detected based on EAR thresholds and blinking patterns.

## Project Structure
```
.
├── drowsiness_detection.py   # Main application script
├── utils.py                  # Utility functions for processing
├── requirements.txt          # Python dependencies
├── models/                   # Pretrained models and datasets
└── README.md                 # Project documentation
```

## Acknowledgments
- OpenCV for image processing.
- dlib for facial landmark detection.
- Python community for various libraries and support.

## Contributing
We welcome contributions! Please follow these steps:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch-name`).
3. Commit your changes (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature-branch-name`).
5. Open a Pull Request.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Contact
For any inquiries, reach out to [saiedhassaan2@gmail.com].

