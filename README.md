---

# Car Counter using YOLOv8 Model

This repository contains code for a car counter built using the YOLOv8 object detection model. The system detects cars in a given video footage and counts them as they pass through a specified region of interest.

## Requirements

To run the code in this repository, you'll need:

- Python 3.x
- OpenCV (cv2)
- NumPy
- [YOLOv8 Model](#https://github.com/ultralytics/ultralytics) - Pre-trained weights and configuration files for YOLOv8
- Stock Footage - [(https://www.vecteezy.com/)](https://videos.pexels.com/video-files/2109463/2109463-hd_1920_1080_30fps.mp4)

## Usage

1. Clone this repository to your local machine:

```
git clone https://github.com/your-username/car-counter.git
```

2. Download the YOLOv8 model files (weights and configuration) and place them in the appropriate directory within the cloned repository.

3. Replace the placeholder for the stock footage with your own footage. Ensure the filename matches the one specified in the code (`stock_footage.mp4`).

4. Run the Python script:

```
python car_counter.py
```

5. Press 'q' to exit the application.

## Features

- Detects cars, trucks, buses, and motorbikes using YOLOv8 model.
- Tracks detected vehicles using the SORT algorithm.
- Counts vehicles passing through a specified region of interest.
- Displays the count of vehicles in real-time on the video feed.

## Contributions

Contributions to improve the functionality, performance, or documentation of this project are welcome. If you encounter any issues or have suggestions for improvements, please open an issue or submit a pull request.

## Credits
cvzone
GitHub: https://bit.ly/3woU6PS (This is a Computer vision package that makes its easy to run Image processing and AI functions. At the core it uses OpenCV and Mediapipe libraries.)
Murtaza Hassan, video on opencv helped me a lot. link: https://www.youtube.com/watch?v=WgPbbWmnXJ8&t=8279s
Tracker function is from 
We will be using a tracker from github repository: https://github.com/abewley/sort/blob/master/sort.py of Alex Bewley.



## License

This project is not licensed and is provided as-is without any warranty. You are free to use, modify, and distribute the code for non-commercial purposes. However, please note that there is no implied support or liability for this project. Use at your own risk.


---
