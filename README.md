# PiVision-App

PiVision is my final-year university project, developed as a Raspberry Pi–based intelligent intruder detection system for home security. The system uses a PIR motion sensor and Raspberry Pi Camera Module to detect motion, identify individuals in real time using computer vision, and capture images and videos of security events. It also provides a live video stream through a mobile application and automatically notifies the user with the identity of the detected person whenever motion is triggered. Developed using Python, Flask, OpenCV, React Native, and Raspberry Pi hardware, PiVision offers a cost-effective, local-first security solution that combines real-time monitoring with intelligent person recognition.

Youtube Link: https://youtu.be/hYp-p3QQm7k?si=oFkPQ05lBc_fyWUW

The aim of this project is to design, build and evaluate a low-cost, self-hosted home security system that gives the user full ownership of their data, accessible remotely through a cross-platform mobile application.

Objectives
1. Develop an application programming interface (API) – a standard way to allow software systems to communicate over the internet using REST on the Raspberry Pi 5. This will enable control of the system, motion events, face management and hardware monitoring.
2. Develop a cross-platform mobile app in React Native & expo that allows users to arm and disarm their security systems, receive alerts and access cameras remotely.
3. Secure the mobile app by integrating firebase authentication; store captured images/video clips from the camera in the cloud using Azure Blob Storage.
4. Motion detection using a pir sensor with night vision capture capability - the system works in both daylight conditions and low-light conditions.
5. Face recognition for identifying motion events as known residents, unknown individuals or general motion.
6. Send real-time push notifications when motion is detected using an external service.
7. Evaluation of the final product against the requirements document and evaluation of overall development process.


<p align="center">
  <img src="https://github.com/user-attachments/assets/cb5be160-d529-4c2f-9a87-ab8d587b6ee7" width="500" /><br/>
  <img src="https://github.com/user-attachments/assets/d0278efb-912d-4622-abe8-fdde0bcc57f0" width="245" />
  <img src="https://github.com/user-attachments/assets/3231c045-ae15-4836-b889-70eca557713d" width="245" />
</p>

