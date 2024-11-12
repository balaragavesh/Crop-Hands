# Crop Hands

**Crop Hands** is a tool that leverages **MediaPipe** and **OpenCV** to automatically detect and crop hands from an image. This cropped hand image can then be used for various downstream tasks, such as gesture recognition, hand posture classification, or any other hand-related classification tasks. This project provides a straightforward way to preprocess images, isolating the hands for further analysis or model training.

## Features

- **Automatic hand detection**: Uses MediaPipe to detect hand landmarks in images.
- **Precise hand cropping**: Isolates the hand region from the image for cleaner input data.
- **Integration-friendly**: Output images are optimized for easy integration into other machine learning pipelines for tasks like classification.

## Getting Started

Follow the steps below to set up the project and start cropping hands from images.

### Prerequisites

Ensure you have **Python 3.x** installed. The project requires some libraries, which can be installed using `requirements.txt`.

### Installation

1. **Clone the Repository**

   ```bash
   git clone https://github.com/yourusername/crop-hands.git
   cd crop-hands
   ```

2. **Install Required Libraries**

   Install the necessary dependencies with:

   ```bash
   pip install -r requirements.txt
   ```

   This will install dependencies like `mediapipe` and `opencv-python`.

### Customization

- **Adjusting crop size**: You can modify the cropping margin around the hand by updating the parameters in the script.

## Contributing

Contributions are welcome! Feel free to open issues or submit pull requests to help improve this project.

## License

This project is licensed under the MIT License.

