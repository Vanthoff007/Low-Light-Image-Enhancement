# Low-Light Image Enhancement Techniques

This repository contains Python code for enhancing low-light images using the MERNET Transformer model. The code demonstrates various image preprocessing techniques, including histogram equalization and contrast-limited Adaptive Histogram Equalization (CLAHE), as well as the application of the MERNET model for low-light image enhancement. The complete explanation can be found [here](https://medium.com/@arjav007/low-light-imaging-techniques-136adf90e21f)

## Prerequisites

Before running the code, ensure that you have the following libraries installed:

- Pillow
- NumPy
- OpenCV
- Matplotlib
- Keras
- Hugging Face Transformers

You can install these libraries using pip: 
```
pip install pillow numpy opencv-python matplotlib keras huggingface_hub
```

## Dataset

You can get the dataset [here](https://drive.google.com/drive/folders/1B0BbUyTSLwhd1WCpt6igIeKZvvtf5E-5?usp=drive_link). The dataset is organized in the following structure:

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
- The low-light image dataset used in this project is from [here](https://paperswithcode.com/dataset/lol).
