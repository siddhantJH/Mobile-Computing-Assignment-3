# Mobile-Computing-Assignment-3

Certainly! Below is an example of a comprehensive README.md file that combines both the orientation tracking app and the image classification app into one document. This README provides detailed instructions on setup, usage, and contribution for the combined Android application.

---

# Android Sensor Data Collection and Image Classification App

This Android application combines two main functionalities: real-time orientation tracking using device sensors and image classification using a convolutional neural network (CNN).

## Features

### Orientation Tracking:
- Collects data from accelerometers and displays real-time orientation angles (pitch, roll, yaw).
- Stores orientation data in a local SQLite database for historical visualization.
- Displays historical orientation data using graphs.

### Image Classification:
- Allows users to select images from the gallery or capture photos using the device camera.
- Preprocesses and classifies images using a pre-trained CNN model via TensorFlow Lite.
- Displays the predicted labels for each image.

## Setup Instructions

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/android-sensor-image-app.git
   ```

2. **Open Project in Android Studio**:
   - Launch Android Studio.
   - Click on `Open an Existing Project` and select the cloned repository directory.

3. **Configure Dependencies**:
   - Ensure that the required dependencies and libraries are properly configured in the `build.gradle` files.

4. **Run the Application**:
   - Connect an Android device or start an emulator.
   - Click on `Run` in Android Studio to install and launch the app on the device/emulator.

## Usage

### Orientation Tracking:
1. **Real-Time Display**:
   - Open the app and observe the real-time orientation angles displayed on the screen.
   - The orientation angles may change dynamically as the device moves.

2. **Historical Visualization**:
   - Navigate to the historical data section in the app.
   - View historical orientation data represented as graphs (pitch, roll, yaw over time).

### Image Classification:
1. **Select or Capture Images**:
   - Tap on `Select Image` to choose an image from the gallery.
   - Alternatively, use the device camera to capture a new image.

2. **Image Classification**:
   - The selected/captured image will be preprocessed and sent through the CNN model.
   - View the predicted labels for the image displayed on the screen.

## Neural Networks API and Model Integration

- The image classification functionality utilizes TensorFlow Lite for loading and running the pre-trained CNN model (`model.tflite`).
- Ensure that the model file is located in the `assets` directory of the Android project.

## Contributing

Contributions to this project are welcome! Here's how you can contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your modifications and commit changes (`git commit -am 'Add new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Create a new Pull Request.

Please ensure that your contributions align with the project's coding standards and guidelines.

## License

This project is licensed under the [MIT License](LICENSE).

---

Feel free to customize this README.md template further based on your specific project details, including additional sections, usage instructions, or acknowledgments. Provide clear and concise information to help users understand and utilize the combined Android application effectively.
