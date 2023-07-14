# IMAGE_SEGMENTATION
PROJECT SETUP
Ensure you have access to a Python environment with the necessary dependencies. It is recommended to use Google Colab for this project as it provides a ready-to-use environment.
Open Google Colab or your preferred Python environment and navigate to the project directory.
Download the dataset or gather the images you wish to perform segmentation on. Place the images in the images folder within the project directory.
(Optional) If you have ground truth masks for your images, place them in the masks folder within the project directory.

# RUNNING
Open the Satellite_Segmentation.ipynb file in Google Colab or your preferred Python environment to run the satellite image dataset
Open the UNET_PET_DATASET.ipynb file in Google Colab to run the pet dataset code.
Modify the necessary parameters at the beginning of the notebook. You can specify the image directory, model hyperparameters, and other settings as required.
Run the notebook cell by cell, following the instructions and comments provided within the code. Make sure to read the comments to understand each step.
Once the code execution is complete, the segmented images will be saved in the output folder within the project directory.

# ADDITIONAL NOTES
The project uses a pre-trained model for image segmentation. By default, the code uses a popular model U-NET, but you can modify the code to use other models or even train your own if desired.
It is recommended to experiment with different hyperparameters, model architectures, and settings to achieve better segmentation results.
The pet dataset code is partially inspired from https://github.com/alnbvy/OxfordPets_Unet.git
The satellite code is partially inspired from https://www.kaggle.com/code/gamze1aksu/semantic-segmentation-of-aerial-imagery?kernelSessionId=120767546
