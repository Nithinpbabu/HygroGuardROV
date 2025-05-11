# HydroGuard  
HydroGuard is an advanced underwater ROV (Remotely Operated Vehicle) designed to monitor and safeguard underwater environments. This innovative system combines real-time data collection, robust underwater navigation, and advanced analytics to ensure efficient monitoring and inspection of submerged concrete Marine structures.  

## STATUS - IN PROGRESS 


## Features  
- **Underwater Crack Detection**: Equipped with sensors and cameras to identify structural damage in submerged structures like dams, pipelines, and bridges.  
- **Real-Time Monitoring**: High-quality live video feed and data transmission for precise underwater inspections.  
- **Depth and Navigation Control**: BLDC motors and Electronic Speed Controllers (ESCs) enable smooth and accurate underwater navigation.  
- **Waterproof Design**: Sealed enclosure to withstand harsh underwater conditions.  
- **Modular Architecture**: Easily expandable with additional sensors or tools to suit specific applications.  
- **Remote Operation**: Controlled via Raspberry Pi for efficient processing and communication.  
- **Incremental Learning**: Saves detected cracks and periodically retrains the existing detection model to improve accuracy and adapt to new scenarios.  


## Technologies Used  
- **Microcontroller / Microprocessors**: Raspberry Pi 5 and ESP32  
- **Motors**: Brushless DC (BLDC) motors with ESCs  
- **Sensors**: Depth sensors, IMU, ultrasonic sensors  
- **Camera**: High-resolution underwater camera  
- **Programming Languages**: Python, C++  
- **Frameworks/Libraries/Tools**:  
  - OpenCV: Image processing  
  - TensorFlow: Analytics and AI integration  
  - YOLO: Object detection and analytics  
  - Flask: Camera streaming and web interface  
  - MQTT Protocol: Data transmission  
  - Google Firebase: Cloud-based data storage and communication  
  

## Applications  
- Inspection of underwater structures such as dams, pipelines, and bridges.  
- Marine research and exploration for environmental studies.  
- Assisting in underwater construction and maintenance projects.  

## Goal  
HydroGuard aims to provide a reliable, efficient, and versatile solution for underwater inspections, contributing to safety, sustainability, and environmental protection.  

# Block Diagram
![WhatsApp Image 2025-01-07 at 11 44 49_729709fa](https://github.com/user-attachments/assets/afcf3cc5-844f-4262-8f25-4f9cdc7466a3)

# Hardware Development
### Stage 1
 **1. Front Dome of ROV**

![dome](https://github.com/user-attachments/assets/1ba59746-89b4-4186-813f-651db0ee2839)

- A 6-inch PVC pipe was carefully cut and sanded to create a smooth base, onto which a durable glass dome was securely attached using industrial-grade epoxy. This formed a robust and waterproof front dome for the ROV.


 **2. Initial Structure**
  
  ![inital structure](https://github.com/user-attachments/assets/edd7670c-33e4-45d0-954e-32490f96dece)

### Stage 2

![WhatsApp Image 2025-01-07 at 12 49 13_32a770ff](https://github.com/user-attachments/assets/22941035-1a90-4ab1-8f47-35949584d7ca)

# Internal Frame of ROV

![frame](https://github.com/user-attachments/assets/7789c2cf-7997-45cf-8c18-f31d774571df)

![frame2](https://github.com/user-attachments/assets/c0e5d8dd-7c21-4b4d-9cd7-919fc5f3b8fd)

![Components in Frame](https://github.com/user-attachments/assets/44a7fc34-0d45-4ea4-bd5c-cd080958af96)

![WhatsApp Image 2025-01-26 at 18 31 46_cabb446c](https://github.com/user-attachments/assets/bca0fe74-c1f1-440f-ac59-cf9825e416e6)

# Rear end of ROV

![1](https://github.com/user-attachments/assets/69081dae-8064-4c00-ab89-f84d25d4290d)

On the Rear end, several ports are given which will give access to the internal components once the ROV is completely enclosed.

- **1.HDMI Port** : connected to the Raspberrypi inside the ROV
- **2.Multi pin Connector** : connected to balanced charging port of LiPo battery
- **3.12v DC socket** : conncetd to Lithium ion Battery pack



![WhatsApp Image 2025-01-14 at 15 41 45_0e6f5767](https://github.com/user-attachments/assets/5bc61f97-f408-4dde-9e92-5bb4495332d5)

![WhatsApp Image 2025-01-14 at 15 41 44_f1e89a63](https://github.com/user-attachments/assets/d6b4dd49-9187-4cf9-8a77-6ee3d3c540bf)

