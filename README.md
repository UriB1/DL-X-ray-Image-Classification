# DL - X-ray Image Classification-
## Overview
This report explores the application of deep learning techniques to classify Chest X-ray images as healthy or unhealthy. The project involves a dataset of 5863 X-ray images categorized into "NORMAL" and "PNEUMONIA" classes. The primary goal is to develop models capable of accurately identifying health status based on X-ray images, first in binary classification (healthy or sick) and then in multi-class classification (differentiating bacterial and viral pneumonia).
The project exploring KNN algorithm with embedding vectors, t-SNE visualization, and applying unsupervised learning for anomaly detection. Each phase offering unique challenges and insights, contributing to a deeper understanding of deep learning in medical imaging applications.

## Data Preparation
### Data Download
The Kaggle API was utilized to download the Chest X-ray dataset efficiently. Two copies were obtained for binary and multi-class models.

### Balancing The Data Sets
To address imbalances, oversampling was performed on the minority class (PNEUMONIA). The balancing act improved model generalization.

### Splitting Data Sets
Data splitting was done with a 80-20 split for training and validation. Directories were organized for binary and multi-class models.

### Directories Reorder
For the multi-class model, directories were restructured based on pneumonia type, enhancing dataset organization.

### Data Generators
Data generators were designed for binary and multi-class classification to preprocess and augment images efficiently during training and evaluation.

## Challenges
### Binary Classification
The binary model achieved 90% accuracy but showed bias. The balancing act improved the F1-score but didn't eliminate bias completely.

### Multi Classification
The multi-class model achieved 85% accuracy, yet it showes low but fair results for all classes after the balancing act in the confusion matrix.

### Image Classification With Embedding Vectors Using KNN
K-Nearest Neighbors was applied to the embedding vectors for additional analysis. The t-SNE visualization revealed challenges in distinguishing classes.

### Unsupervised Learning With Anomaly Detection
An auto-encoder was employed for anomaly detection. The model showed promising results (70% accuracy) in distinguishing healthy and pneumonia-affected images.

## Improvements Process
Various experiments were conducted to optimize model parameters, including learning rate, epochs, batch size, and network architecture.

## Setup
1. Open and save a copy of the Google Colab notebooks in your Google Drive.
3. Open a Kaggle account and create an API token for fetching the data set (or download the data to your local device and change the code accordingly). 
2. Check all paths within the code and make them suitable for your personal use.
4. Modify and train the models as you please.

## Acknowledgments
* The project database is hosted by Kaggle and can be accessed at the [attached link](https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia).
* During the project, the Google Collab platform was used to gain access to GPU's to train the various models.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contributing
Feel free to contribute by opening issues or creating pull requests.

## Author
[UriB1](https://github.com/UriB1)
