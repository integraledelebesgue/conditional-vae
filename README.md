# Conditional Convolutional Variational Autoencoder
This repository contains a simple variational autoencoder used to generate handwritten digits based on the `MNIST` dataset.  
The architecture of a simple CNN-based VAE has been modified according to the idea of *conditioning*, based on the paper [*Learning Structured Output Representations from Attributes using Deep Conditional Generative Models*](https://www.researchgate.net/publication/370469525_Learning_Structured_Output_Representations_from_Attributes_using_Deep_Conditional_Generative_Models). This allows generating arbitrary digits by providing class labels to the decoder.

## Installation:
> [!important]
> The project is managed by `uv`. I strongly recommend using it for installation and usage, not only for this project but for **all your Python software**.

To run the notebook:
1. Clone the repository:
```shell
git clone https://github.com/integraledelebesgue/conditional-vae.git
cd conditional-vae
```
2. Install the dependencies and create the virtual environment:
```shell
uv sync
```
