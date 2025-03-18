

# Style Transfer using AlexNet

This repository contains a style transfer project that applies the artistic style of Van Gogh's paintings to a cat image using **AlexNet**. The project demonstrates how to blend the content of one image with the style of another using deep learning techniques.

## Features

- **Style Transfer**: Combines the content of one image with the style of another.
- **AlexNet**: Uses a pre-trained AlexNet model for feature extraction.
- **Van Gogh Style**: Applies the artistic style of Van Gogh's paintings to a cat image.
- **Easy to Use**: Includes scripts for style transfer and visualization.

## Usage

1. Clone the repository:
   

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run style transfer:
   

## Requirements

- Python 3.x
- TensorFlow 2.x
- NumPy
- OpenCV
- Matplotlib

Example `requirements.txt`:
```plaintext
tensorflow>=2.0.0
numpy>=1.19.0
opencv-python>=4.5.0
matplotlib>=3.3.0
```

## Example

Input:
```bash
python style_transfer.py --content data/cat.jpg --style data/vangogh.jpg --output output/stylized_cat.jpg
```

Output:
- A stylized image saved as `output/stylized_cat.jpg`.

