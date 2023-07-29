# Object Detection Android App

![Logo](https://github.com/deepakdevengineer/Object-Detection-App/assets/129176978/78775f7a-432f-404c-83d3-682011a10d35)


This Android app is designed to detect objects in real-time using the camera of your device. It utilizes the power of TensorFlow Lite and is equipped with pre-trained machine learning models for object detection. You can choose between multiple models, including MobileNet SSD, EfficientDet Lite 0, EfficientDet Lite 1, and EfficientDet Lite 2, all trained on the COCO dataset.

## Features

- Real-time object detection through the device's camera.
- Multiple models available for different accuracy and performance trade-offs.
- Utilizes quantized models for efficient inference.
- Bounding boxes and class labels are displayed for detected objects.
- User-friendly interface with easy-to-understand instructions.

## Getting Started

Follow these instructions to build and run the Object Detection Android app on your physical Android device.

### Prerequisites

- Android Studio IDE installed on your development machine (tested on Android Studio Bumblebee).
- Physical Android device with developer mode enabled and a minimum OS version of SDK 24 (Android 7.0 - Nougat).

### Building and Running the App

1. Open Android Studio and select "Open an existing Android Studio project."

2. Navigate to the `tensorflow-lite/examples/object_detection/android` directory and click "OK."

3. If prompted for Gradle Sync, proceed with it.

4. Connect your Android device to your computer and ensure that developer mode is enabled.

5. Click the green "Run" arrow in Android Studio to install and run the app on your connected Android device.

### Model Selection

The app comes with pre-trained models that are downloaded and managed automatically during the build process. You can choose from the following models:

- MobileNet SSD: A lightweight model suitable for real-time object detection on resource-constrained devices.
- EfficientDet Lite 0, 1, and 2: These models offer improved accuracy while still maintaining reasonable performance.

### Usage

1. Launch the app on your Android device.

2. Point the camera towards the objects you want to detect.

3. The app will analyze the camera feed and draw bounding boxes around detected objects, along with their corresponding class labels.

4. Explore the performance of different models by selecting them from the app's settings.

### Customization

If you want to customize the app or use your own TensorFlow Lite models, follow these steps:

1. Replace the existing model files in the `assets` folder with your desired models (ensure they are compatible with TensorFlow Lite).

2. Modify the app's code to load and use your custom models, adjusting the input and output requirements accordingly.

### Technologies Used

- TensorFlow Lite: For efficient and fast object detection on Android devices.
- Android CameraX API: For capturing images from the device's camera.
- Android UI Components: For building an intuitive user interface.

## Contributing

Contributions to the project are welcome! If you encounter any issues or have suggestions for improvements, feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License. Please see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- TensorFlow team for providing TensorFlow Lite and pre-trained object detection models.
- COCO dataset for enabling the training of accurate object detection models.

---

Thank you for using our Object Detection Android app! We hope you find it useful and enjoy exploring the world of object recognition. If you have any questions or feedback, don't hesitate to reach out. Happy detecting!
