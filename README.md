🍎 Fruit Recognition System

A robust machine learning system for automated fruit identification and classification using deep learning and computer vision techniques.

 📋 Overview

This project leverages advanced machine learning and image processing techniques to develop an intelligent system capable of accurately identifying and classifying fruits. The system combines Convolutional Neural Networks (CNNs) with feature extraction techniques to analyze fruit images and distinguish them based on shape, color, texture, and size.

 ✨ Key Features

- High Accuracy: Achieved 99.75% validation accuracy on 141 fruit classes
- Real-time Processing: Optimized for efficient inference and classification
- Robust Feature Extraction: Uses CNN and DCT-based feature extraction
- User-friendly Interface: Clean, intuitive GUI for image upload and results display
- Comprehensive Dataset: Trained on 14,100 images across 141 fruit categories

🎯 Applications

- Agriculture & Horticulture: Automated fruit sorting and grading after harvesting
- Food Processing: Quality control in packaging and processing plants
- Retail & Supermarkets: Inventory management and quality assurance
- Export & Quality Control: Compliance with international quality standards
- Research & Development: Agricultural research and crop variety development

 🏗️ System Architecture

 Core Components

1. **Image Acquisition Module**
   - High-resolution camera integration
   - Support for multiple image formats (JPEG, PNG)
   - Real-time image capture capabilities

2. **Preprocessing Module**
   - Image resizing and normalization
   - Noise reduction and enhancement
   - Data augmentation techniques

3. **Feature Extraction Module**
   - CNN-based automatic feature learning
   - DCT (Discrete Cosine Transform) for frequency domain analysis
   - Traditional methods (HOG, SIFT) support

4. **Classification Module**
   - Deep CNN architecture for fruit classification
   - Support Vector Machine (SVM) alternative
   - 141 fruit class recognition

5. **User Interface Module**
   - Image upload and capture interface
   - Results display with confidence scores
   - Classification history and analytics

 📊 Performance Metrics

 Model Performance
- **Validation Accuracy**: 99.75%
- **Validation Loss**: 0.0118
- **Training Images**: 11,280
- **Validation Images**: 2,820
- **Total Classes**: 141

 DCT-based Model
- **Validation Accuracy**: 74.57%
- **Validation Loss**: 0.8685

 🛠️ Technology Stack

- **Deep Learning Framework**: TensorFlow/Keras
- **Image Processing**: OpenCV
- **Programming Language**: Python
- **Machine Learning**: scikit-learn
- **UI Framework**: Tkinter/Flask
- **Data Processing**: NumPy, Pandas

 📦 Installation

 Prerequisites
- Python 3.7 or higher
- pip package manager

Setup Steps
1. Clone the repository from GitHub
2. Navigate to the project directory
3. Create a virtual environment for the project
4. Activate the virtual environment
5. Install all required dependencies from requirements.txt

 Required Dependencies
- TensorFlow 2.8.0 or higher
- OpenCV Python 4.5.0 or higher
- NumPy 1.21.0 or higher
- Matplotlib 3.5.0 or higher
- scikit-learn 1.0.0 or higher
- Pillow 8.3.0 or higher
- Tkinter for GUI
- Flask for web interface

 🚀 Usage

 Command Line Interface
Run the main application by executing the main.py file. For web interface, execute the app.py file.

### Python API Integration
The system provides a simple API that allows you to initialize the FruitClassifier with a path to the trained model, then use the predict method to classify fruit images. The system returns the predicted fruit class along with confidence scores.

 📁 Dataset

The system is trained on a comprehensive dataset containing:
- **Total Images**: 14,100
- **Fruit Classes**: 141 different varieties
- **Categories Include**: 
  - Various apple varieties (Braeburn, Golden, Granny Smith, etc.)
  - Citrus fruits (Orange, Lemon, Lime, Grapefruit)
  - Tropical fruits (Mango, Pineapple, Papaya, etc.)
  - Berries (Strawberry, Blueberry, Raspberry)
  - Stone fruits (Peach, Plum, Cherry)
  - And many more...

 📈 Model Architecture

 CNN Architecture Flow
The system follows a hierarchical structure starting with an Input Layer that receives the fruit image, followed by multiple Convolutional Layers for feature extraction, Pooling Layers for dimensionality reduction, Feature Extraction layers for pattern recognition, Fully Connected Layers for classification logic, and finally an Output Layer that produces results for all 141 fruit classes.

 Mathematical Foundations

Image Normalization: The system normalizes input images by subtracting the minimum pixel value and dividing by the range between maximum and minimum values.

CNN Forward Pass: Each layer processes the input through weight multiplication, bias addition, and activation function application.

📊 Results

 Training Results
- Exceptional performance with minimal overfitting
- Stable training with consistent validation metrics
- Model generalizes well to unseen data

 Comparison Analysis
| Model Type | Accuracy | Loss | Processing Speed |
|------------|----------|------|------------------|
| CNN Only   | 99.75%   | 0.0118 | Fast |
| CNN + DCT  | 74.57%   | 0.8685 | Medium |

 🔮 Future Enhancements

 Planned Improvements
1. Edge Device Optimization
   - MobileNet/EfficientNet integration
   - Model quantization for mobile deployment
   - Real-time processing on embedded systems

2. Dataset Expansion
   - Additional fruit varieties
   - Diverse lighting conditions
   - Multiple angles and orientations

3. Advanced Features
   - Ripeness detection
   - Defect identification
   - Size and weight estimation

4. Integration Capabilities
   - IoT device connectivity
   - Cloud-based processing
   - API development for third-party integration

 🤝 Contributing

We welcome contributions! Please follow these steps:

1. Fork the repository
2. Create a feature branch for your new feature
3. Commit your changes with descriptive messages
4. Push to your feature branch
5. Open a Pull Request with detailed description

 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
 👥 Authors

- Addepalli Ajay Sai - *Electrical Engineering, IIT Palakkad*
- Dr. Sabarimalai Manikandan - *Project Supervisor, IIT Palakkad*

 🙏 Acknowledgments

- Indian Institute of Technology Palakkad
- Fruits 360 Dataset contributors
- TensorFlow and OpenCV communities
- All contributors and supporters of this project

