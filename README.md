# Spiking-Classifier

Spiking Neural Network Image Classification with SNN-Torch and Gradio
This project demonstrates the use of Spiking Neural Networks (SNNs) for image classification, by utilizing the SNN-Torch library. SNNs are biologically inspired models that emulate the spiking behavior of neurons, providing energy-efficient computation. The repository includes a pre-trained SNN model and an interactive demo powered by Gradio.

## Demo
The demo can be found in this [Demo Google Colab Notebook](https://colab.research.google.com/drive/1jTGcoD2uFWfw-1giMwlRk9o2IW6EMFue?usp=sharing)
The Training process can be found in this [Training Google Colab Notebook](https://colab.research.google.com/drive/1JfQ9f0UAsYXfFmOIZBVc-rRJPu8JDTsj?usp=sharing)

## Project Structure
* Model_App.ipynb: This notebook contains the code to deploy the SNN model using Gradio.
* README.md: The readme file you are currently reading, it provides an overview of the project.
* SNN_Image_Classifier.ipynb: This notebook contains the code for creating and training an SNN model for image classification.
* SNN_Model.pth: The pre-trained SNN model saved in PyTorch's .pth format. This model is used in the Gradio app for image classification.
* requirements.txt: A list of required Python packages and libraries needed to run the notebooks locally. Install these dependencies using pip install -r requirements.txt.

## Resources
[SNN-Torch Documentation](https://snntorch.readthedocs.io/en/latest/): Learn more about SNNs and how to use SNN-Torch in the official documentation.
[SNN-Torch GitHub Repository](https://github.com/jeshraghian/snntorch/tree/master): Explore the SNN-Torch library on GitHub.