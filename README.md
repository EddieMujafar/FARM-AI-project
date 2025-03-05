# Mujafar-Farm AI

## Introduction
Mujafar-Farm AI is a project aimed at utilizing artificial intelligence to classify images of farm animals. This project leverages ONNX for model inference and PyTorch for image preprocessing.

## Features
- Image classification using a pre-trained ONNX model.
- Supports various farm animals.
- Provides confidence scores for predictions.

## Installation
To get started with Mujafar-Farm AI, follow these steps:

1. Clone the repository:
    ```sh
    git clone https://github.com/EddieMJ/mujafar-farm-ai.git
    ```

2. Navigate to the project directory:
    ```sh
    cd mujafar-farm-ai
    ```

3. Install the required dependencies:
    ```sh
    pip install -r requirements.txt
    ```

## Usage
To classify an image using the ONNX model, follow these steps:

1. Place the image you want to classify in the `TEST` directory.

2. Run the classification script:
    ```sh
    python classify_with_onnx.py
    ```

3. The script will output the predicted class index, label, and confidence score.

## Files
- `classify_with_onnx.py`: Script for classifying images using the ONNX model.
- `model.onnx`: The pre-trained ONNX model.
- `labels.txt`: File containing the class labels.
- `TEST/`: Directory to place images for classification.

## Contributing
Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements
- [ONNX Runtime](https://onnxruntime.ai/)
- [PyTorch](https://pytorch.org/)
- [Pillow](https://python-pillow.org/)
