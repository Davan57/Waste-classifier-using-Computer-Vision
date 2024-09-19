# Waste Classifier using Neural Network

## Overview

The "Waste Classifier using Neural Network" project is a desktop application for classifying waste items using a neural network model. The application leverages a Tkinter-based GUI to interact with users and a camera feed to capture images for classification. The classifier is built using a Support Vector Classifier (SVC) from scikit-learn, with the option to add new data, train the model, and make predictions.

## Features

- **Camera Integration**: Capture real-time images using a webcam.
- **Image Classification**: Classify captured images into predefined categories.
- **Training**: Train the model using images collected through the application.
- **Auto Prediction**: Automatically predict classes based on real-time camera feed.
- **GUI Controls**: Interactive buttons to save images, train the model, reset data, and toggle auto prediction.

## Installation

### Prerequisites

Ensure you have Python 3.x installed. You will also need the following Python libraries:

- `opencv-python`
- `numpy`
- `Pillow`
- `scikit-learn`
- `tkinter` (included with Python standard library)

### Setup

1. **Clone the Repository**

   ```sh
   git clone https://github.com/yourusername/waste-classifier.git
   cd waste-classifier
   
### Install Dependencies

You can install the required Python libraries using pip:

```sh
pip install opencv-python numpy Pillow scikit-learn
```

# Run the main.py script to launch the application:

```sh
python main.py
```
### Interact with the GUI

**Auto Prediction**: Toggle auto-prediction to automatically classify images from the camera feed.
**Save for Class**: Save captured images to train the model for each class.
**Train Model**: Train the model with the collected images.
**Predict**: Make a prediction based on the current camera feed.
**Reset**: Clear saved images and reset counters.
**Class Names**:On startup, you will be prompted to enter names for three classes. These names will be used to label the saved images and predictions.

### Code Structure

**main.py**: Entry point for the application.
**app.py**: Contains the App class which defines the GUI and application logic.
**model.py**: Contains the Model class for training and predicting using the Support Vector Classifier (SVC).
**camera.py**: Contains the Camera class for handling webcam input.

### Development
## Running Tests
Ensure your code works as expected by running the application and verifying functionality. Automated tests can be added as needed.

### Contributing
Contributions are welcome! Please fork the repository and submit a pull request with your proposed changes.

### License
This project is licensed under the MIT License. See the LICENSE file for more details.

### Acknowledgements
**OpenCV**: For image processing and camera integration.
**scikit-learn**: For the Support Vector Classifier (SVC) model.
**Pillow**: For image handling in Python.


