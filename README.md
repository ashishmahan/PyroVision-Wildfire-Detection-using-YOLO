# PyroVision: Wildfire Detection using YOLO

**Overview**

PyroVision is an innovative project aimed at leveraging deep learning techniques to detect wildfires in real-time using the YOLO (You Only Look Once) object detection algorithm. Wildfires are devastating natural disasters that can cause massive destruction to ecosystems, wildlife, and human infrastructure. Early detection and rapid response are crucial to minimizing the damage caused by these fires.

This project utilizes the YOLOv8 architecture to accurately and efficiently identify and locate potential wildfire hotspots in images or video feeds. By detecting wildfires at an early stage, PyroVision can assist in activating timely responses, potentially saving lives and preserving nature.

**Key Features**

Real-time Detection: Capable of processing live video feeds or static images to detect wildfire occurrences in real time.

High Accuracy: YOLOv8 provides state-of-the-art accuracy, ensuring reliable detection of even small-scale fires.

Efficient Model: YOLO's efficiency allows for fast processing, making it suitable for deployment in resource-constrained environments such as drones or edge devices.

Scalability: The model can be adapted to work with various input sources, including satellite imagery, CCTV cameras, or mobile devices.

**Technologies Used**

YOLOv8: The latest version of the YOLO object detection algorithm, known for its speed and accuracy.

Python: The core programming language used for implementing the model.

OpenCV: A powerful library for real-time computer vision tasks.

TensorFlow/PyTorch: Frameworks for building and training the deep learning model.

Streamlit: For creating an interactive web application to demonstrate the wildfire detection capabilities.



**Dataset**

The model was trained on a custom dataset that includes images of wildfires in various environments, weather conditions, and scales. The dataset was augmented and preprocessed to improve the model's robustness against false positives and varying environmental factors.


*How It Works*

Input: The system takes images or video streams as input.

Detection: YOLOv8 processes the input and identifies regions where wildfires are likely present.

Output: The model outputs bounding boxes around detected wildfire regions, along with a confidence score indicating the likelihood of a wildfire.


*Applications*

Early Warning Systems: Integrating PyroVision into early warning systems for forest management and disaster response.
Surveillance: Deploying the model on drones or fixed surveillance cameras for continuous monitoring of fire-prone areas.
Environmental Monitoring: Using satellite images to monitor large forests and detect wildfires at a larger scale.



**Getting Started**

To get started with PyroVision, follow these steps:

**Clone the Repository:**

git clone https://github.com/ashishmahan/PyroVision-Wildfire-Detection-using-YOLO.git

cd PyroVision-Wildfire-Detection-using-YOLO

**Install Dependencies:**

pip install -r requirements.txt

**Run the Model:**

python detect.py --source [path_to_image_or_video]

Visualize Results: Use the provided Streamlit app to visualize detection results in real-time.

**Contributing**

We welcome contributions to enhance the capabilities of PyroVision. If you have suggestions, bug reports, or improvements, feel free to create a pull request or open an issue.
