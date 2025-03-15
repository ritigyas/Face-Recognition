# Facial Recognition Dataset Collection and Preprocessing

This project captures labeled facial images using Google Colab, stores them in Google Drive, and preprocesses them for machine learning applications.

## Features
- **Automated Image Capture**: Uses webcam to capture labeled facial images.
- **Dataset Organization**: Stores images in structured folders within Google Drive.
- **Dataset Validation**: Ensures each label has images before training.
- **Image Preprocessing**: Resizes and normalizes images for model training.
- **Dataset Splitting**: Splits images into training and testing datasets while maintaining class balance.
- **Visualization**: Displays sample images with labels for verification.



## Usage
1. **Capture Labeled Photos**:
   - Run the script and enter a person's name.
   - Click "Capture" to take photos.
   - Save multiple images per person.
   - Type 'q' to quit.

2. **Validate the Dataset**:
   - Ensures each class has at least one image.
   - Warns if a folder is empty.

3. **Preprocess Images**:
   - Loads images and converts them into arrays.
   - Resizes images to (128x128) and normalizes pixel values.

4. **Split Dataset**:
   - Uses `train_test_split` to divide data (80% training, 20% testing).
   - Maintains class balance using stratified sampling.

5. **Visualize Images**:
   - Displays sample images with labels for verification.

## Technologies Used
- **Python**: Core scripting language.
- **Google Colab**: Cloud-based execution.
- **OpenCV & PIL**: Image handling.
- **NumPy**: Array manipulation.
- **Matplotlib**: Data visualization.
- **TensorFlow/Keras**: Image preprocessing.
- **Scikit-learn**: Dataset splitting.

## Screenshots
# Dataset
![image](https://github.com/user-attachments/assets/4a468cd8-e2d3-44e2-9568-d12bcb97299b)


## Future Enhancements
- Implement real-time face detection for auto-cropping.
- Integrate face recognition models for classification.
- Add augmentation techniques for dataset enhancement.
- Deploy the model for live recognition applications.

This project provides a structured pipeline for collecting and preparing facial recognition datasets, ensuring high-quality data for machine learning models.

