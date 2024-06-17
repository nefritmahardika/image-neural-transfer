# Image Neural Transfer Project

## Project Overview

Image Neural Transfer is a project that applies the principles of neural style transfer to blend the style of one image with the content of another. This technique leverages deep learning, particularly convolutional neural networks (CNNs), to create visually stunning artworks by combining the artistic style of one image (style image) with the content of another image (content image).

## Team Members

- Muhammad Nefrit
- Rafa Agustant
- Farhan Karisma
- Ecki Fawwaaz
- Naufal Fakhri
- Jaya Goval

## Objectives

The main objectives of this project are:
1. Implement a neural style transfer algorithm using a pre-trained deep learning model.
2. Enable users to generate stylized images by merging the content and style of their chosen images.
3. Provide an intuitive interface for users to upload images and adjust parameters to customize the output.

## Requirements

To run this project, you need the following software and libraries installed:

- Python 3.6 or higher
- TensorFlow
- Keras
- NumPy
- Matplotlib
- Pillow

You can install the required libraries using the following command:

```sh
pip install tensorflow keras numpy matplotlib pillow
```

## Usage

1. **Clone the Repository**: Clone the repository to your local machine.
   ```sh
   git clone https://github.com/nefritmahardika/image-neural-transfer.git
   cd image-neural-transfer
   ```

2. **Prepare Images**: Place your content image and style image in the `images` directory. Ensure they are in a supported format (e.g., JPEG, PNG).

3. **Run the Notebook**: Open and run the `neural-transfer.ipynb` notebook. You can execute the notebook cells in sequence to perform the neural style transfer.

4. **Adjust Parameters**: Optionally, you can adjust parameters such as the number of iterations, content weight, and style weight in the notebook cells.

## Example

Here is an example of how to set parameters and run the neural transfer in the notebook:

```python
content_path = 'images/content.jpg'
style_path = 'images/style.jpg'
iterations = 1000
content_weight = 1e3
style_weight = 1e-2
```

## Results

The project successfully produces images that combine the desired content and style. The quality of the output images can be fine-tuned by adjusting the parameters and the number of iterations.
<img width="562" alt="Screenshot 2024-06-17 at 11 31 08" src="https://github.com/nefritmahardika/image-neural-transfer/assets/70056209/a9ca1cd4-3b45-48ad-a687-dfd07d74aac8">

