[//]: # (Image References)

[image1]: ./images/sample_dog_output.png "Sample Output"
[image2]: ./images/vgg16_model.png "VGG-16 Model Keras Layers"
[image3]: ./images/vgg16_model_draw.png "VGG16 Model Figure"


## Project Overview

The below project involves the learning of building a convolutional deep neural network to classify user-supplied images.  Given an image of a dog, the algorithm will identify an estimate of the canine’s breed.  If supplied an image of a human, the code will identify the resembling dog breed.  

![Sample Output][image1]

## For code, please go through the "dog_app.ipynb" file present above.


## Project Instructions

### Instructions

1. Clone the repository and navigate to the downloaded folder.
2. Download the [dog dataset](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/dogImages.zip), [human dataset](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/lfw.zip) and [VGG-16 bottleneck features](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/DogVGG16Data.npz). Unzip to `path/to/dog-project/dogImages`, `path/to/dog-project/lfw` and `path/to/dog-project/bottleneck_features` respectively.
3. Obtain the necessary Python packages using "pip install -r /path/to/requirements/requirements-gpu.txt" if using a CUDA based GPU or "pip install -r /path/to/requirements/requirements.txt" for a CPU execution.
4. Open the notebook (requires Annaconda3 to be installed locally) and follow the instructions.
	
	jupyter notebook dog_app.ipynb

This project was built on NVIDIA GTX960, if GPU is a limitation please use an
AWS EC2 instance.






