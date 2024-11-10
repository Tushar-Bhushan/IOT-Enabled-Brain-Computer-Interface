# IOT-Enabled-Brain-Computer-Interface
# Project Overview
This IoT-Enabled Brain-Computer Interface (BCI) project provides a cost-effective platform for capturing, analyzing, and transmitting EEG signals in real-time, designed for educational and research applications. Leveraging IoT, the system enables remote monitoring and data visualization, supporting applications like emotion recognition, cognitive load assessment, and neurofeedback.

# Key Features
EEG Signal Acquisition: Uses the ADS1299 ADC to capture and digitize EEG signals.
Real-Time Data Transmission: Powered by an ESP32 microcontroller, the system streams data to Google Firebase Realtime Database for global access.
Data Visualization: Visualizes real-time EEG data through BrainVision Viewer, integrated with Lab Streaming Layer (LSL) for efficient streaming.
Educational & Research Applications: Enables multiple EEG-based studies, including driver state monitoring, speller programs, and meditation analysis.

# System Components
EEG Signal Acquisition Setup:
Electrodes placed following the 10-20 system.
ADS1299 ADC for signal digitization with high accuracy and low noise.
OpenBCI Mark IV headset customized with dry electrodes for convenience.
ESP32 Microcontroller:
Runs FreeRTOS for reliable data processing and transmission.
Manages data upload to Firebase for remote access.
Google Firebase Realtime Database:
Stores and provides real-time access to EEG data.
Integrates with a React-based frontend for visualization.
Data Visualization:
Uses BrainVision Viewer to observe EEG patterns and perform FFT analysis.

# Applications and Demonstrations
Emotion Recognition: Detects emotional states from EEG signals, useful for mental health applications.
Cognitive Load Assessment: Measures mental workload in real-time, supporting productivity and user experience studies.
Driver State Monitoring: Monitors alertness and drowsiness, promoting road safety.
Meditation and Mindfulness Training: Provides feedback during meditation, aiding relaxation and concentration.

# Setup & Usage
Hardware Setup:
Mount electrodes as per the 10-20 system, connect to the ADC, and assemble with the ESP32.
Firebase Setup:
Configure Google Firebase Realtime Database to enable data storage and retrieval.
ESP32 Code Configuration:
Flash the ESP32 with the provided firmware to handle data acquisition, processing, and Firebase integration.
Visualization Setup:
Install BrainVision Viewer and LSL library for real-time data visualization and analysis.

# Software Details
ESP32 Firmware: Controls data acquisition and transmission, including ADC configuration and Firebase database interactions.
Firebase Database: Stores EEG data for real-time access and integrates with web-based applications.
Future Improvements
Scalability: Increase the number of EEG channels for more detailed monitoring.
Enhanced Data Processing: Incorporate machine learning for improved data interpretation and classification.
User Interface Enhancements: Develop an intuitive interface for educational users and researchers.

# Documentation
For detailed technical insights, hardware schematics, and software code, please refer to the full Documentation provided with this project.
