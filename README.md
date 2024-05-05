# Low-Light Image Enhancement using MERNET Transformer

This repository contains Python code for enhancing low-light images using the MERNET Transformer model. The code demonstrates various image preprocessing techniques, including histogram equalization and Contrast Limited Adaptive Histogram Equalization (CLAHE), as well as the application of the MERNET model for low-light image enhancement.

## Prerequisites

Before running the code, ensure that you have the following libraries installed:

- Pillow
- NumPy
- OpenCV
- Matplotlib
- Keras
- Hugging Face Transformers

You can install these libraries using pip: 
```pip install pillow numpy opencv-python matplotlib keras huggingface_hub```

## Dataset

The code assumes that you have a dataset containing low-light and high-light image pairs. The dataset should be organized in the following structure:

```
LOLdataset/
our485/
high/
image1.png
image2.png
...
low/
image1.png
image2.png
...
```

Make sure to update the paths in the code to match the location of your dataset.

## Usage

1. Clone the repository or download the code files.
2. Update the paths in the code to match the location of your dataset.
3. Run the code cells in the provided order.

The code includes the following functionality:

- Loading and displaying random pairs of low-light and high-light images from the dataset.
- Applying histogram equalization and CLAHE on the low-light images for contrast enhancement.
- Loading and using the MERNET Transformer model for low-light image enhancement.
- Visualizing the input low-light image, the enhanced image, and the corresponding high-light image.

## Contributing

Contributions to this project are welcome. If you find any issues or have suggestions for improvement, please open an issue or submit a pull request.

## Acknowledgments

- The MERNET Transformer model was obtained from the Hugging Face Transformers library.
- The low-light image dataset used in this project is from [source/citation].
