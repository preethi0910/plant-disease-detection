# Plant Disease Detection

## Overview
Plant Disease Detection is an AI-powered system that helps farmers and agricultural experts identify plant diseases early. The system uses deep learning techniques to analyze images of plant leaves and detect diseases accurately.

## Features
- Image-based disease detection
- Identifies multiple plant diseases
- Provides confidence scores for predictions
- User-friendly interface for farmers
- Can suggest potential treatments

## Technologies Used
- Python
- TensorFlow/Keras
- NumPy
- OpenCV
- Matplotlib
- PIL (Python Imaging Library)
- Kaggle API (for dataset retrieval)

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/plant-disease-detection.git
   cd plant-disease-detection
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
3. Download the dataset from Kaggle:

  - Upload your Kaggle API key (kaggle.json) in the notebook.
  - Run the dataset download cell.
    
4. Run the model training:
   ```bash
   python train.py
5. Start the web application:
   ```bash
   python app.py
## Dataset
The project uses a labeled dataset from Kaggle containing images of healthy and diseased leaves. The dataset is preprocessed and augmented for better training results.

## Model Training
- Uses Convolutional Neural Networks (CNN) for classification.
- Random seed is initialized for reproducibility.
- Data augmentation is applied to improve model performance.
- Evaluation metrics include accuracy, precision, recall, and F1-score.

## Usage
1. Upload an image of a plant leaf.
2. The AI model will analyze and detect if the plant is healthy or diseased.
3. If diseased, the system will suggest possible remedies.

## Future Enhancements
- Integration with a mobile app for real-time detection.
- More plant species and diseases added to the dataset.
- AI-based treatment recommendations.

## Contributing
Feel free to fork the repository and contribute by submitting pull requests.
