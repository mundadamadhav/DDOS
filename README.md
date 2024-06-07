# DDOS
Destributed Denial of Service Attack Detection using machine learning under SDN Context
Project Overview
This project aims to develop a robust system for detecting Distributed Denial of Service (DDoS) attacks using machine learning techniques within a Software-Defined Networking (SDN) framework. By leveraging SDN's centralized control and machine learning's pattern recognition capabilities, the system can dynamically monitor network traffic, identify anomalies, and mitigate potential DDoS attacks efficiently.

Features
Real-time Traffic Monitoring: Continuously analyze network traffic for potential DDoS attacks.
Machine Learning Integration: Utilize algorithms like decision trees, SVM, and neural networks for anomaly detection.
Dynamic Response: Automatically adjust network policies to mitigate detected threats.
Scalability: Designed to handle large-scale networks and high traffic volumes.
Extensibility: Easy to integrate with existing network management tools and protocols.
Architecture
Data Collection: Capture network traffic data using SDN controllers.
Feature Extraction: Process raw data to extract relevant features for analysis.
Machine Learning Model: Train models to distinguish between normal and attack traffic.
Detection Engine: Deploy the trained model in the SDN controller to monitor traffic in real-time.
Mitigation: Implement network policy changes to mitigate detected DDoS attacks.
Technologies Used
Programming Languages: Python
Machine Learning Libraries:  Scikit-learn
SDN Frameworks: OpenFlow, Ryu SDN Controller, Mininet
