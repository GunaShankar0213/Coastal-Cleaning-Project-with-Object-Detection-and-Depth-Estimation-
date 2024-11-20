# Plastic Waste Detection in Coastal Environments

## Project Overview

This project focuses on developing an advanced system to detect and manage plastic waste in coastal environments using AI and sensor technologies. The system integrates various machine learning models, including YOLO for object detection, MiDAS for depth estimation, and OnePose for 6D pose estimation. The aim is to detect, classify, and estimate the size and depth of plastic waste in coastal regions, with a particular emphasis on buried plastic waste in sandy environments. 

### Why I Made This Project
Plastic waste has become one of the biggest environmental challenges, especially in coastal areas where it poses a severe threat to marine life and ecosystems. Traditional methods of detecting and cleaning plastic waste are often inefficient and limited in scope. The goal of this project is to leverage cutting-edge technologies like machine learning and computer vision to provide a more effective solution to detect and manage plastic waste in real time.

### Skills Gained
Through this project, I gained valuable experience in several areas:

- **Machine Learning and AI Integration**: Developing custom pipelines that combine multiple models for object detection, depth estimation, and 6D pose estimation.
- **Computer Vision**: Working with state-of-the-art models like YOLO for object detection and MiDAS for depth estimation, which is critical for detecting buried objects in sandy environments.
- **Model Fine-Tuning and Evaluation**: Fine-tuning models for real-world environments and evaluating them using metrics like precision, recall, and mAP.
- **Sensor Integration**: Exploring ways to integrate sensors for depth estimation and pose detection, which can help improve accuracy in real-world applications.
- **Real-Time Monitoring**: Implementing a real-time monitoring system that integrates object detection with depth estimation for continuous waste monitoring.
  
---

## Project Structure

### Chapter 1: Introduction
- **1.1 The Global Plastic Waste Crisis in Coastal Environments**: This chapter discusses the alarming levels of plastic waste in coastal regions and the environmental impact it has.
- **1.2 Leveraging Advanced Technologies for Plastic Detection**: Explores how machine learning and AI can be used to improve plastic waste detection.
- **1.3 Future Prospects and Potential Applications**: Discusses future applications of AI and IoT in plastic waste management, including real-time tracking and autonomous cleanup systems.
- **1.4 Future Objective and Potential Applications**: Outlines the project's goals of improving the accuracy and real-time monitoring of plastic waste detection.
- **1.5 Scope of the Project**: Covers the project's approach of using YOLO, MiDAS, and OnePose models to address the detection of buried plastic objects.
- **1.6 Challenges**: Highlights the technical challenges of detecting buried plastic, integrating multiple models, and ensuring real-time performance.

### Chapter 2: Background Study
- **2.1 Literature Review**: Reviews existing literature on plastic waste detection technologies and the use of AI for environmental conservation.
- **2.2 Themes and Gaps Identified**: Identifies key themes and gaps in the existing research, particularly in detecting buried objects in sandy environments.

### Chapter 3: Methodology
- **3.1 Overview**: Describes the hybrid methodology combining YOLO for object detection, MiDAS for depth estimation, and OnePose for 6D pose estimation.
- **3.2 Dataset Sources**: Outlines the datasets used for training the models, including publicly available datasets and custom datasets collected from coastal environments.
- **3.3 Data Preparation**: Discusses the data cleaning and augmentation techniques used to prepare images for training.
- **3.4 Initial Model Development**: Details the development of YOLO and MiDAS models.
- **3.5 Combining Models and Fine-Tuning**: Explains how the models were integrated into a unified pipeline and fine-tuned.
- **3.6 Deployment and Real-Time Monitoring**: Covers the deployment of the system for real-time monitoring of plastic waste.

![image](https://github.com/user-attachments/assets/f396e543-f622-41fb-a19a-61f615edc22a)


### Chapter 4: Implementation
- **4.1 Data Augmentation**: Discusses the techniques used to augment training data, improving the model’s ability to generalize.
- **4.2 Training and Fine-Tuning the YOLO Models**: Describes the training process for YOLO models and fine-tuning to improve detection accuracy.
- **4.3 Evaluation Metrics**: Details the metrics used to evaluate the model’s performance, such as precision, recall, and F1 score.
- **4.4 Comparison of YOLO Models**: Compares various YOLO versions (YOLOv3, YOLOv4, YOLOv5) for optimal performance.
- **4.5 Implementation of Detective Pipelines**: Explains the implementation of the detection pipeline for plastic waste identification.

### Chapter 5: Integration of Depth Estimation for Object Detection with MiDAS
- **5.1 Fine-Tuning and Preparing the MiDAS Model**: Describes how MiDAS was fine-tuned to estimate the depth of objects.
- **5.2 Running the Depth Estimation on Detected Object Regions**: Explains how depth estimation was applied to detected plastic waste to assess its size and depth.
- **5.3 Integrating Depth Estimation into the Detection of Buried Objects**: Discusses how depth estimation helps improve the detection of buried objects.
- **5.4 Deployment and Real-Time Monitoring**: Covers the deployment of the depth estimation model in real-time systems.

![image](https://github.com/user-attachments/assets/303fc6d4-64fd-4cc7-81b2-edd1bae49bee)

### Chapter 6: OnePose Model for Object Detection and 6D Pose Estimation
- **6.1 Theory Behind OnePose Model**: Introduces the OnePose model for 6D pose estimation.
- **6.2 6D Pose Estimation Workflow**: Outlines the workflow for estimating the 6D pose of detected objects.
- **6.3 Mathematical Formulation of OnePose**: Explains the mathematical principles behind OnePose.
- **6.4 OnePose for Object Detection in Coastal Waste Management**: Discusses the application of OnePose for better detection and localization of plastic waste in coastal areas.

![tins_png rf 2c62054e20ad1d2c59fd602c3dc32a09](https://github.com/user-attachments/assets/537baf8b-eb59-4e3f-9a95-55b6ce98fecf)

### Chapter 7: Results
Presents the results of the models, showcasing performance metrics, sample outputs, and visualizations that demonstrate the effectiveness of the integrated models.

### Chapter 8: Conclusion
Summarizes the findings, highlighting the successful integration of object detection, depth estimation, and 6D pose estimation models for detecting plastic waste in coastal regions. The potential impact of this system on environmental conservation is also discussed.

### Chapter 9: Limitations and Future Work
- **9.1 Limitations**: Discusses limitations such as model accuracy in complex environments and the challenge of detecting small or deeply buried objects.
- **9.2 Future Work**: Outlines plans for improving accuracy, expanding the system's capabilities, and integrating drones for large-scale real-time monitoring.

---

## Future Drone Integration and Sensors

In the future, drones equipped with advanced sensors could be integrated into this system to enhance plastic waste detection. Drones can cover large areas quickly, capturing high-resolution images and transmitting them to the detection pipeline. By integrating depth sensors, LiDAR, and thermal cameras, drones could detect plastic waste more efficiently, even in challenging environments like sand or water. This integration would enable real-time waste monitoring and automated clean-up operations, making coastal waste management more effective and sustainable.

The potential use of drones would include autonomous waste collection, real-time monitoring of large coastal areas, and faster response times in areas with heavy plastic contamination. Integrating AI-driven detection systems with drone hardware and sensors will provide scalable solutions to tackle the growing issue of plastic pollution.

---

## Conclusion

This project demonstrates how cutting-edge technologies can be leveraged to address the global plastic waste crisis in coastal environments. By integrating AI, computer vision, and sensor technologies, this system offers a promising solution for detecting and managing plastic waste in real time, potentially revolutionizing waste management practices in coastal regions. The future integration of drones and advanced sensors will further enhance the system’s capabilities, making it a powerful tool for environmental conservation.
