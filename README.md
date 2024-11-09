## AI-Powered Virtual Mouse Using Hand Gesture Recognition
An AI-powered virtual mouse that leverages hand gesture recognition to enable hands-free control of a computer system. This project uses computer vision to detect and interpret hand gestures, providing an accessible and interactive way to perform basic mouse functions without physical contact.

## About
The AI-Powered Virtual Mouse project utilizes computer vision and hand gesture recognition to create a touch-free, accessible alternative to a traditional mouse. Built using machine learning libraries like OpenCV and MediaPipe, this system captures hand movements through a webcam and interprets them as mouse actions such as moving the cursor, clicking, and scrolling. The project aims to enhance human-computer interaction, making it especially useful in environments where hands-free control is beneficial, such as for individuals with limited mobility or in settings requiring contactless technology.

## Features
Hands-Free Mouse Control: Allows users to control mouse functions (move, click, scroll) through hand gestures without physical contact.
Gesture Recognition: Utilizes hand-tracking technology to detect and interpret various hand gestures.
Customizable Gestures: Offers the potential for users to define custom gestures for different actions.
Real-Time Feedback: Provides immediate response to hand movements, enhancing user experience and precision.
Accessibility-Focused: Designed with accessibility in mind, especially for users with limited mobility or in settings where contactless interaction is preferred.
Multi-Device Compatibility: Potential for integration across different operating systems and devices with camera support.
## Requirements
Programming Language: Python 3.7+
Libraries:
OpenCV: For image processing and real-time computer vision functionalities
MediaPipe: For efficient and accurate hand tracking
PyAutoGUI: To perform virtual mouse actions based on recognized gestures
Hardware:
Webcam (in-built or external) for capturing hand gestures
System requirements: Moderate CPU and memory to handle real-time processing
IDE: Any Python-compatible IDE (e.g., PyCharm, VS Code, Jupyter Notebook)
## System Architecture
Input Capture:
The system starts by capturing video frames from a webcam, which provides a continuous stream of hand movements.
Hand Detection and Tracking:

Using MediaPipe, the system detects hands within each frame. This component identifies landmarks on the hand to track the position and orientation in real-time.
Gesture Recognition:

With OpenCV and machine learning algorithms, specific hand gestures (e.g., finger positions or distance between fingers) are recognized as predefined actions (like mouse clicks, cursor movement, and scrolls).
Command Execution:

Based on the detected gesture, PyAutoGUI performs the corresponding virtual mouse actions on the computer, such as moving the cursor, clicking, or scrolling.
Feedback Loop:

The real-time feedback loop continuously updates the system, allowing seamless and responsive interaction with the virtual mouse through hand gestures.
## Output
![Screenshot 2024-11-09 182306](https://github.com/user-attachments/assets/dc30da34-46c8-470c-8c4a-0f94890ea232)


#### Output1 - Name of the output

![Screenshot 2024-11-09 182335](https://github.com/user-attachments/assets/c5cfc2c7-f4e0-4654-b2d6-19e98fc5d5d0)
![Screenshot 2024-11-09 182430](https://github.com/user-attachments/assets/ea518cae-7d87-40a3-bf34-dbc59fc41776)


#### Output2 - Name of the output
![Screenshot 2024-11-09 182525](https://github.com/user-attachments/assets/12f90a1a-1f2e-42c0-b5a8-f9e9c9734bf0)
![Screenshot 2024-11-09 182545](https://github.com/user-attachments/assets/b083b1ff-5af1-4d6e-9cbb-bcfa3e320908)


Detection Accuracy: 90%



## Results and Impact :
- **Results**:
   - The AI-powered virtual mouse demonstrated accurate and responsive gesture recognition in real-time, allowing users to control mouse actions seamlessly with hand movements.
   - Testing showed reliable detection of gestures like moving the cursor, clicking, and scrolling, achieving a high degree of precision and usability across different lighting conditions and hand positions.
   - Performance metrics indicate an accuracy rate of approximately XX% for gesture recognition, providing a smooth user experience with minimal latency.

- **Impact**:
   - **Accessibility**: This virtual mouse system enhances accessibility, enabling individuals with limited mobility to interact with computers without traditional input devices.
   - **Hygienic Control**: In environments requiring minimal physical contact, such as medical facilities, this contactless interaction offers a more hygienic alternative to conventional mice.
   - **Advancement in Human-Computer Interaction (HCI)**: By using intuitive hand gestures, the project contributes to evolving interfaces that make HCI more natural and immersive.
   - **Potential for Multi-Device Integration**: The underlying technology can be expanded to control multiple devices, benefiting applications in gaming, VR/AR environments, and smart home systems.

This system’s impact underscores its potential as an assistive technology, driving further innovation in contact-free, gesture-based interaction methods.
## Articles published / References
**Articles Published / References**

1. **Real-Time Virtual Mouse using Hand Gestures for Unconventional Environment**  
   This study from IEEE explores real-time gesture recognition techniques and their application in virtual mouse systems. It provides valuable insights into algorithms that enhance responsiveness and accuracy.  
   [Read more on IEEE Xplore](https://ieeexplore.ieee.org/document/10308331).

2. **Virtual Mouse Using Hand Gestures**  
   This paper presents an implementation of a virtual mouse based on hand gestures using OpenCV and MediaPipe, discussing both technical challenges and performance evaluations.  
   [Available on IEEE Xplore](https://ieeexplore.ieee.org/document/9673251).

3. **AI Virtual Mouse Using Hand Gesture Recognition**  
   Published in the International Journal of Research Publication and Reviews, this article covers the technical setup of an AI-powered virtual mouse, including gesture-to-action mappings using OpenCV and PyAutoGUI.  
   [Access here](https://ijrpr.com/). 

These references offer a strong foundation for understanding gesture-based virtual mouse systems, covering techniques, results, and applications.



