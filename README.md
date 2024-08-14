# Cats-vs-Dogs Classification Using Tensorflow and Keras
This project demonstrates how to classify images of cats and dogs using the TensorFlow and Keras libraries. The Cats vs Dogs dataset from TensorFlow was used for training, validation, and testing of the model.

## Dataset
The dataset used in this project is the Cats vs Dogs dataset from TensorFlow. The dataset was divided into three parts:

    Training set: 70% of the total dataset
    Validation set: 20% of the total dataset
    Test set: 10% of the total dataset

### Citation
    @Inproceedings (Conference){asirra-a-captcha-that-exploits-interest-aligned-manual-image-categorization,
    author = {Elson, Jeremy and Douceur, John (JD) and Howell, Jon and Saul, Jared},
    title = {Asirra: A CAPTCHA that Exploits Interest-Aligned Manual Image Categorization},
    booktitle = {Proceedings of 14th ACM Conference on Computer and Communications Security (CCS)},
    year = {2007},
    month = {October},
    publisher = {Association for Computing Machinery, Inc.},
    url = {https://www.microsoft.com/en-us/research/publication/asirra-a-captcha-that-exploits-interest-aligned-manual-image-categorization/},
    edition = {Proceedings of 14th ACM Conference on Computer and Communications Security (CCS)},
    }

## Data Preprocessing
The data was pre-processed by resizing the images to 128 x 128, followed by normalizing the images.

## Model Architecture
The model was built using a Convolutional Neural Network (CNN) architecture with TensorFlow and Keras. The architecture includes several convolutional layers followed by max-pooling layers, and fully connected layers leading to the output.

## Results
### Training Set
    Accuracy: 0.9171
    Loss: 0.19

### Validation Set
    Accuracy: 0.8556
    Loss: 0.32

### Testing Accuracy & Loss
    Accuracy: 0.856
    Loss: 0.40
