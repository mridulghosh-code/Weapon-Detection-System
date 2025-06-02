# Weapon-Detection-System
The Weapon Detection System is a real-time intelligent surveillance solution designed to identify and classify potential weapons in video footage or images. The system leverages deep learning-based computer vision models to improve public safety and threat assessment in high-security zones such as airports, schools, banks, and government buildings.

# Key Features:
1. Real-time weapon detection in CCTV/video feed
2. Classification of different weapon types (e.g., pistol, no_weapon, knife)
3. Custom-trained dataset of 5,000+ annotated images
4. High accuracy through transfer learning using EfficientNet and NASNetMobile
5. Lightweight deployment with YOLOv8n for real-time inference
6. Alerts are integrated for automated security notifications

# Technical Highlights:
1. Model Architecture: Feature extraction using EfficientNet; classification backbone with NASNetMobile
2. Training: 100 epochs, batch size of 32; optimized using Adam optimizer and data augmentation
3. Evaluation: Achieved high accuracy and low false-positive rate on the test dataset
4. Deployment: Tested on Google Colab and capable of integration with edge devices or cloud APIs

# Outcome:
1. Successfully demonstrated real-time detection of concealed and visible weapons
2. Reduced detection latency while maintaining precision and recall balance
3. Potential integration into existing smart surveillance systems
