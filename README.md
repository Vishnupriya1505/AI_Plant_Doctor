AI_Plant_Doctor
AI Plant Doctor is a deep learning-based system that detects plant leaf diseases using image classification. The model analyzes leaf images and predicts the disease along with suggested treatments, helping farmers and agricultural enthusiasts take timely action.

Features
 Detects diseases from leaf images
 Built using MobileNetV2 (Transfer Learning)
 Real-time image prediction
 Provides treatment suggestions
 Displays confidence score
 Supports image upload (Colab / Web app)
 
Tech Stack
Python
TensorFlow / Keras
NumPy
Google Colab

Dataset
Source: PlantVillage Dataset
Used subset of crops:
Potato (Early blight, Late blight, Healthy)
Tomato (Early blight, Late blight, Healthy)

Model Details
Architecture: MobileNetV2
Input Size: 224 × 224
Output Classes: 6
Loss Function: Sparse Categorical Crossentropy
Optimizer: Adam

How It Works
Upload a leaf image
Model processes the image
Predicts:
Crop type 
Disease 
Confidence 
Displays treatment suggestion

Applications
Smart farming
Agricultural advisory systems
Early disease detection
Farmer assistance tools

Author
Vishnupriya S
