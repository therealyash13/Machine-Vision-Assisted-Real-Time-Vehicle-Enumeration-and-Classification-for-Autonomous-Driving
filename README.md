# Machine Vision-Assisted Real-Time Vehicle Enumeration and Classification for Autonomous Driving

====================================================
Intelligent Vehicle Detection and Counting System
====================================================

This repository contains the code and data for the intelligent vehicle detection and counting system, which aims to accurately detect and count vehicles on highways using computer vision techniques and deep learning models. The system utilizes a newly proposed high-definition highway vehicle dataset, which includes annotated tiny objects for training deep learning-based vehicle detection models.

Contact: yashwanthbalan75@gmail.com

Table of Contents
-----------------
1. Introduction
2. Installation
3. Usage
4. Dataset
5. License

1. Introduction
----------------
The intelligent vehicle detection and counting system presented in this project addresses the challenge of accurately detecting and counting vehicles of various sizes on highways. The system leverages computer vision techniques and deep learning models, specifically the YOLOv3 network, for vehicle detection. Additionally, the ORB algorithm is utilized to track vehicle trajectories, enabling the determination of driving direction and the count of different vehicles.

2. Installation
----------------
To set up the intelligent vehicle detection and counting system, follow these steps:

- Clone the repository: `git clone https://github.com/your-username/repository-name.git`
- Install the required dependencies: `pip install -r requirements.txt`

3. Usage
---------
The intelligent vehicle detection and counting system consists of the following components:

- Code Files: Contains the Python scripts for vehicle detection, counting, and trajectory tracking.
- Input Files: Includes the input images or videos on which the system will perform vehicle detection and counting.
- DataSet: Contains the high-definition highway vehicle dataset used for training the deep learning models.

To use the system, follow these steps:

1. Place the input images or videos in the Input Files folder.
2. Run the vehicle detection and counting script using the command: `python detect_count.py`
3. The system will process the input files, detect vehicles, track trajectories, and output the results.

4. Dataset
----------
The high-definition highway vehicle dataset used in this project is included in the DataSet folder. The dataset consists of 328K images, with annotated tiny objects for accurate vehicle detection. This dataset provides a solid foundation for training deep learning models specifically designed for highway vehicle detection.

5. License
----------
This project is licensed under the Apache License 2.0. For more information, please refer to the `LICENSE` file included in this repository.

For any inquiries or questions, please contact yashwanthbalan75@gmail.com.

