# AIPlane2

GAN model trained to generate images of Aircrafts. The model is trained on https://www.robots.ox.ac.uk/~vgg/data/fgvc-aircraft/

## Model
This repository only holds the colab used to train the model.

More details about the model (including model weights) can be found at https://huggingface.co/PrakhAI/AIPlane2

## Demo
A demo app for this model is hosted at https://huggingface.co/spaces/PrakhAI/AIPlane2 (please "Restart this Space" if prompted).

The demo showcases two kinds of image generation:

### Generate Random
This samples random latent vectors to generate images.
<img width="630" alt="Screenshot 2023-08-20 at 11 44 17 PM" src="https://github.com/prakharbanga/AIPlane2/assets/1158196/686d365f-8be5-4ad5-857f-0688bc058947">

### Generate Similar
This is conditional on an previously generated image, and lets the user explore similar images.
<img width="663" alt="Screenshot 2023-08-20 at 11 44 02 PM" src="https://github.com/prakharbanga/AIPlane2/assets/1158196/91d665a5-9556-4c90-9d53-cc3c5b229de5">
