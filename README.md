# IOT-Enabled-Brain-Computer-Interface
IoT-Enabled Brain-Computer Interface (BCI)
Project Overview
This IoT-Enabled Brain-Computer Interface (BCI) project provides a cost-effective BCI platform designed to capture, analyze, and transmit EEG signals for educational and research purposes. Leveraging IoT technologies, this system enables real-time remote monitoring and control, enhancing accessibility and usability in various applications such as emotion recognition, cognitive load assessment, and neurofeedback.

Key Features
EEG Signal Acquisition: Uses an ADS1299 Analog-to-Digital Converter (ADC) to capture and digitize EEG signals.
Real-Time Data Transmission: Powered by an ESP32 microcontroller, the system streams data to a Google Firebase Realtime Database for global access.
Data Visualization: Data can be visualized in real-time using BrainVision Viewer software, integrated with the Lab Streaming Layer (LSL) for efficient streaming and display.
Educational & Research Applications: Supports multiple EEG-based use cases, such as driver state monitoring, speller programs, and meditation analysis.
System Components
EEG Signal Acquisition Setup:
Electrodes placed following the 10-20 system.
ADS1299 ADC for signal digitization with high accuracy and low noise.
OpenBCI Mark IV headset customized with dry electrodes for user convenience.
ESP32 Microcontroller:
Runs FreeRTOS for reliable data processing and transmission.
Manages data upload to Google Firebase for remote access.
Google Firebase Realtime Database:
Stores and provides real-time access to EEG data.
Integrates seamlessly with a React-based frontend for visualization.
Data Visualization:
Uses BrainVision Viewer to observe EEG patterns and perform Fast Fourier Transform (FFT) analysis for deeper insights.
Applications and Demonstrations
Emotion Recognition: Detects emotional states from EEG signals, useful for mental health applications.
Cognitive Load Assessment: Measures mental workload in real-time, enhancing productivity and user experience studies.
Driver State Monitoring: Monitors alertness and drowsiness, promoting road safety.
Meditation and Mindfulness Training: Provides feedback for meditation practices, aiding relaxation and concentration.
Setup & Usage
Hardware Setup:
Mount electrodes as per the 10-20 system, connect to the ADC, and assemble with the ESP32.
Firebase Setup:
Configure Google Firebase Realtime Database to enable data storage and retrieval.
ESP32 Code Configuration:
Flash the ESP32 with provided firmware to handle data acquisition, processing, and Firebase integration.
Visualization Setup:
Install BrainVision Viewer and LSL library for real-time data visualization and analysis.
Software Details
ESP32 Firmware: Controls data acquisition and transmission. Includes code to configure ADC and manage Firebase database interactions.
Firebase Database: Provides a scalable solution for storing EEG data and enables seamless integration with web-based applications.
Future Improvements
Scalability: Increase the number of EEG channels for more detailed monitoring.
Enhanced Data Processing: Incorporate advanced machine learning algorithms to improve data interpretation and classification.
User Interface Enhancements: Develop an intuitive interface to better serve educational users and researchers.
Documentation
For detailed technical insights, hardware schematics, and software code, please refer to the full Documentation provided with this project.
