# Automated Human - Wildlife Monitoring System using Deep Learning

## ABSTRACT
In many real-life applications animal detections-based research is very essential. Methods for 
animal detection are helpful to know about the moving behavioural of targeted animal and to 
prevent animal intrusion that result dangerous situations in forest border area. Human animal 
conflict creates lot of negative impact for both human and wild animal. Crop damage caused 
by animal attacks is one of the major threats in reducing the crop yield. Due to the expansion 
of cultivated land into previous wildlife habitat, crop raiding is becoming one of the most 
antagonizing human-wildlife conflicts. Farmers in India face serious threats from pests, natural 
calamities & damage by animals resulting in lower yields. Traditional methods followed by 
farmers are not that effective and it is not feasible to hire guards to keep an eye on crops and 
prevent wild animals. Since safety of both human and animal is equally vital, it is important to 
protect the crops from damage caused by animal as well as divert the animal without any harm. 
So, there is a need of developing a system which detect any presence of interactions of wild 
animal in the border region and without causing any harmful effect to human being and wild 
animal the interference and the dangerous situations caused by the wild animal have to be 
minimized. This project covers various perspective of the design of such systems, including 
image processing and artificial intelligence for animal detection, species classification, 
automatic identification of animal using Yolov3, a pretrained CNN model and design of alarm unit using Bolt IoT WiFi Module.

## INTRODUCTION
Human-wildlife conflict requires striking a balance between conservation of wild-animal and the needs of people who live with wildlife. Urbanization of our society has increased the personal interaction between human and wildlife. The problematic result is that our society is causing more problems from wildlife but becoming less concerned about the well-being of wildlife species. So, this project mainly aims forest border security which will consider well-being of both humans in the border region and wild animals. Here develops wildlife monitoring tool based on YOLOv3 and an animal repellent circuit. When the system detects the presence of animal it produces an alarm to inform the people and the forest rangers. So here further a system is designed which helps to repel animal back to the forest. Ultrasonic sensor is used for this purpose. We know that an ultrasonic sensor continuously produces ultrasonic wave. The frequency of ultrasonic wave is about 40 kHz, which is beyond the audible range of human being and animal can easily hear this sound. Which create a hostile and noisy environment for the animal and by hearing this noisy sound animal get repel back to the forest. 

### 1.1 Purpose
Human-wildlife conflict requires striking a balance between conservation of wild-animal and the needs of people who live with wildlife. Urbanization of our society has increased the personal interaction between human and wildlife. The problematic result is that our society is causing more problems from wildlife but becoming less concerned about the well-being of wildlife species. So, this project mainly aims forest border security which will consider well-being of both humans in the border region and wild animals. Here develops wildlife monitoring tool based on YOLOv3 and an animal repellent circuit. When the system detects the presence of animal it produces an alarm to inform the people and the forest rangers. So here further a system is designed which helps to repel animal back to the forest. Ultrasonic sensor is used for this purpose. We know that an ultrasonic sensor continuously produces ultrasonic wave. The frequency of ultrasonic wave is about 40 kHz, which is beyond the audible range of human being and animal can easily hear this sound. Which create a hostile and noisy environment for the animal and by hearing this noisy sound animal get repel back to the forest.

### 1.2 Intended Audience and Document Overview 
The intended audience for this document is the project team, stakeholders, and anyone involved in the development and implementation of the Automated Human-Wildlife Conflict Monitoring System using Deep Learning. This includes researchers, developers, engineers, and individuals interested in wildlife conservation and mitigating human-wildlife conflicts. This document provides an overview of the project titled "Automated Human-Wildlife Conflict Monitoring System using Deep Learning." It outlines the objectives, scope, and key components of the system. The document also describes the pre-trained model, YOLOv3, which is used for object detection, and the integration of a Bolt IoT Wi-Fi module and a piezo buzzer for immediate response.

### 1.3 Scope
The scope of the  project encompasses the development and implementation of a system that can detect and classify animals in real-time using the YOLOv3 pre-trained model. The system aims to mitigate human-wildlife conflicts by providing immediate responses when animals from specified classes are detected.
The key components within the scope of the project include: 

1. **Object Detection:** The system utilizes the YOLOv3 model for object detection, specifically focusing on the detection of five animal classes: elephant, cat, zebra, bear, and dog. The model should accurately identify and localize these animals within input images or video feeds. 

2. **Classification and Decision-Making:** Once an animal is detected, the system classifies it into one of the predefined classes. If the detected animal belongs to the specified classes, further action is triggered. 

3. **Bolt IoT Wi-Fi Module Integration:** The system integrates a Bolt IoT Wi-Fi module, which serves as a communication medium between the software and the physical device. It receives signals from the system to activate the connected piezo buzzer. 

4. **Piezo Buzzer:** The system activates a piezo buzzer connected to the Bolt IoT Wi-Fi module. The buzzer emits specific irritating sounds depending on the animal class detected. These sounds are intended to deter or repel the detected animals. 

5. **Monitoring and Logging:** The system may include functionality to log instances of animal detections and the corresponding actions taken. This data can be useful for analysis, evaluating system performance, and informing decision-making.

## LITERATURE REVIEW 
### 2.1 Existing Systems
1. E. Znidersic, "Camera Traps are an Effective Tool for Monitoring Lewin’s Rail
(Lewiniapectoralisbrachipus)<br><br>
  a. Camera traps have gained popularity in wildlife monitoring and surveys because of their
  efficiency in collecting wildlife images without monitoring.<br>
  b. Using camera traps located to maximize detection probability, images from 1,213 camera
  events quantified Lewin's Rail occurrence and temporal variation in activity.<br>
  c. Although camera traps cannot replace other avian survey methods, they provide a
  complementary method for collecting behavioral data on Lewin's Rail and other
  ecologically similar species.<br><br>
2. Duhart C, Dublon G, Mayton B, and Paradiso J. ‘Deep Learning Locally Trained Wildlife
Sensing in Real Acoustic Wetland Environment’. In Thampi SM, Marques O, Krishnan S,
Ciuonzo D and Kolekar MH (eds.), Advances in Signal Processing and Intelligent Recognition
Systems, 2019: 3–14.<br><br>
  a. Identifying the sound of animals and processing it by concepts of signal processing and
  deep learning.<br>
  b. This article presents the entire Tidzam system, which has been designed in order to
  identify in real-time the ambient sounds of weather conditions as well as sonic events
  such as insects, small animals and local bird species from microphones deployed on the
  site.<br>
  c. This experiment provides insight on the usage of deep learning technology in a real
  deployment.<br><br>
3. Santhiya S, Dhamodharan Y, Kavi Priya NE,. Santhosh CS and Surekha M. ‘A Smart
Farmland Using Raspberry Pi Crop Prevention and Animal Intrusion Detection System ‘.
International Research Journal of Engineering and Technology (IRJET), 2018; 05(03)<br><br>
  a. Camera interfaced to the raspberry pi module. Camera is used to captures an image of
  wild animal and send captured image to the Raspberry pi module.<br>
  b. When image taken by the raspberry pi, it is compared with database image. After
  comparing images, if the wild animal is detected then it gives commands to GSM (Global
  System for Mobile communication) module.<br>
  c. GSM used to send the message to the owner of the farm. To get the output in the form of
  audio, connect raspberry pi to the speaker.<br><br>
