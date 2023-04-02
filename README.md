
# Vehicle Count

The Vehicle Tracking project is an advanced computer vision system developed using Supervision that utilizes cutting-edge technologies such as YOLOv8 and ByteTracker to accurately detect and count vehicles in real-time video streams. By leveraging YOLOv8's object detection capabilities and ByteTracker's advanced tracking algorithms, the system is able to identify and track vehicles with high accuracy. The system is highly customizable, allowing users to adjust the parameters of the tracking algorithm to suit their specific needs. The output of the system is a visually appealing video stream that displays the vehicles being tracked. The system is built using the latest technologies in computer vision and machine learning, and is designed to be highly scalable, making it suitable for use in a wide range of applications, from traffic management to security surveillance.

## Snippet

![Example GIF](https://github.com/Umar-Saeed-97/Vehicle-Count/blob/main/Data/Example%20Results/test1.gif)

## Requirements

The following packages are required to run the notebook:

- numpy
- opencv-python
- ultralytics
- supervision

You can install these packages and dependencies using the following pip command:

```bash
    pip install -r requirements.txt
```

## Usage

Here's how you can use the code in this project:

1. Clone or download the repository to your local machine.

2. Open the Jupyter Notebook file in the repository.

3. Run the cells in the notebook to make detections.

4. You can modify the code to fit your needs.

## Model

This project utilizes the popular YOLOv8 object detection model, which is pretrained on the COCO dataset and achieves high accuracy and speed by dividing the input image into a grid. Additionally, ByteTracker is used for vehicle tracking, a simple and efficient online multi-object tracking algorithm that combines detection and tracking in a unified framework. No custom training was done in this project.

## License

MIT

## Author

[Umar Saeed](https://www.linkedin.com/in/umar-saeed-16863a21b/)