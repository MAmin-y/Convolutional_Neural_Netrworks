# CNN-Based Image Classification

Below are detailed explanations for each part of the project.

## Part 1: CNN for Skin Lesion Cancer Detection

In this part, a convolutional neural network (CNN) is developed to classify skin lesions as cancerous or non-cancerous using dermoscopic images. The approach follows the methodology outlined in the paper "Early Detection of Skin Cancer Using Convolutional Neural Networks" (refer to [PubMed](https://pubmed.ncbi.nlm.nih.gov/39095688/) for details). The project begins with extensive image preprocessing where the dataset—sourced from collections such as HAM10000—is normalized and augmented to enhance training diversity. The network architecture is designed according to the paper’s recommendations, including tailored layers to capture critical features of skin lesions. After training, the model’s performance is rigorously evaluated using metrics like the confusion matrix, ROC curves, and F1-score, with a comparative analysis between the obtained results and those reported in the reference paper.

## Part 2: Bean Leaf Disease Detection Using Transfer Learning

The second part of the project addresses the detection of diseases in bean leaves by leveraging transfer learning. This papers follows the approach of "Classification of Beans Leaf Diseases using Fine Tuned CNN Model" (refer to [ScinceDirect](https://www.sciencedirect.com/science/article/pii/S1877050923000170) for details).A dataset of bean leaf images is preprocessed using standard techniques, including resizing, normalization, and further enhanced through data augmentation via the Albumentations library to mitigate overfitting. Several pre-trained models—specifically NasNet, MobileNetV2, and EfficientNetB6—are fine-tuned on this dataset to adapt them to the specific characteristics of bean leaf disease identification. The training involves experimenting with different optimizers and hyperparameters to optimize model performance. Evaluation metrics such as accuracy, precision, recall, and ROC analysis are computed to compare the effectiveness of each model, and the results are consolidated to highlight the most effective approach for the task.

