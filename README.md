# ML-Capstone

## Project Overview
Use of machine learning to to analyze and classify patient chest X-ray photos on whether they appear normal, or appears infected with pneumonia. 
The model is trained to detect opacity in chest X-ray images, a comon indicator of Pneunmonia infection. We leveraged Densenet architecture as a base model due to its feature processin, allowing for greater accuracy and computational efficiency when categorising images. 

## Benchmark Model
We used a Convolutional Neural Network (CNN) model as our benchmark. CNN excels at image processing due to it's ability to analyze grid-like structure of an image's pixels and the RGB values within. As it is one of the most widely used image processing and classification models, at the time of this research, it serves as an ideal benchmark for comparing our model's performance. 

## Evaluation Metrics
To asses our model's performance, we used the following metrics: 
- **Accuracy**: Depicts the percentage of correct prediction being made by our model.
- **Recall**: The models actual ability to identify actual positive (pneumonia) cases.
- **Confusion Matrix**: Provide metrics on True Positives, False Positives, False Negatives, and True Negatives.

## Dataset
[Chest X-Ray Images (Pneumonia)](https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia)

## Contributors 
- Alex Geer
- David Turineck
- James Pagett
