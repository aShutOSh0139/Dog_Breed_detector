# Dog Breed Detector

Welcome to the **Dog Breed Detector** project! This project tackles a multiclass classification problem and can identify over 120 different breeds of dogs with an accuracy of 99%. The project is an extension of the [MobileNetV2](<https://tfhub.dev/google/imagenet/mobilenet_v2_130_224/classification/4>) model, trained using the [dog breed identification dataset](<https://www.google.com/url?q=https%3A%2F%2Fwww.kaggle.com%2Fc%2Fdog-breed-identification%2Fdata>) from Kaggle.

## Contents

- `dog-vision-model.ipynb`: This Jupyter notebook contains the detailed documentation and code for:
  - Data modification and preprocessing.
  - Importing, modifying, and compiling the model.
  - Creating callbacks.
  - Training the model, creating tensor boards, and improving the model.
  - Saving, loading, and testing the model.
  
- `Dog-Breed-Testing.ipynb`: This notebook explains how to load and use the trained model to identify the breed of your custom dog images. **YOU CAN TRY IT...!!!**

- `<logs (link)>` folder: Contains training logs.

- `<CustomImgs (link)>` folder: Contains custom images for testing in the `Dog-Breed-Testing.ipynb` file.

- `<Dogs (link)>` folder: Contains tested images for the `dog-vision-model.ipynb` file.

## Important Note
**The trained model is 22 MB in size and is not uploaded to this repository.** You can download the trained model from the following link: [Trained Model (Link)](<Trained_Model_Link>).

The test results CSVs from `dog-vision-model.ipynb` are uploaded on Google Drive: [Test Results (Link)](<test_results_link>).

## Usage

### `dog-vision-model.ipynb`

This file contains:

- Data modification and preprocessing steps.
- Details on importing, modifying, and compiling the model.
- Creation of callbacks.
- Training data, tensor board creation, and model improvements.
- Instructions for saving, loading, and testing the model.

### `Dog-Breed-Testing.ipynb`

To use the model for identifying dog breeds from your custom images, follow these steps:

1. Download the `Dog-Breed-Testing.ipynb` file and the [Trained Model (Link)](<Trained_Model_Link>).
2. If you want to use the model locally:
   - Open Anaconda Prompt and activate your environment.
   - Install the necessary packages:
     ```bash
     pip install tensorflow tensorflow_hub numpy pandas matplotlib
     ```
   - Open the Jupyter notebook file (`Dog-Breed-Testing.ipynb`) and modify the paths for the trained model and custom images folder.

Alternatively, you can use Google Colab without the need for local installations.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
