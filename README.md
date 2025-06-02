# Weapon-Detection-System
The Weapon Detection System is a real-time intelligent surveillance solution designed to identify and classify potential weapons in video footage or images. The system leverages deep learning-based computer vision models to improve public safety and threat assessment in high-security zones such as airports, schools, banks, and government buildings.

# Key Features:
Real-time weapon detection in CCTV/video feed
Classification of different weapon types (e.g., pistol, rifle, knife)
Custom-trained dataset of 5,000+ annotated images
High accuracy through transfer learning using EfficientNet and NASNetMobile
Lightweight deployment with YOLOv8n for real-time inference
Alerts are integrated for automated security notifications

# Technical Highlights:
Model Architecture: Feature extraction using EfficientNet; classification backbone with NASNetMobile
Training: 100 epochs, batch size of 32; optimized using Adam optimizer and data augmentation
Evaluation: Achieved high accuracy and low false-positive rate on the test dataset
Deployment: Tested on Google Colab and capable of integration with edge devices or cloud APIs

Outcome:
Successfully demonstrated real-time detection of concealed and visible weapons
Reduced detection latency while maintaining precision and recall balance
Potential integration into existing smart surveillance systems
