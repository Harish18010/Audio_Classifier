## Audio Classifier

This project uses a Convolutional Neural Network (CNN) to automatically classify short audio recordings  sounds into one of ten predefined categories . The model learns to recognize patterns in the sound data by converting each audio clip into a visual format called a Mel Spectrogram, which captures frequency and timing information. These spectrograms are then treated like grayscale images and passed through a CNN, a type of deep learning model commonly used for image classification. This approach demonstrates how techniques from computer vision can be applied to solve audio classification problems effectively.

## Dataset

I used the dataset UrbanSound8K from kaggle : [Dataset](https://www.kaggle.com/datasets/chrisfilo/urbansound8k). All rights belong to the original authors.

## Description

- This project uses a **Convolutional Neural Network (CNN)** to classify urban audio clips into one of 10 categories.
- The dataset used is **UrbanSound8K**, which contains thousands of short sound recordings labeled with real-world classes
- Each audio file is converted into a **Mel Spectrogram** — a 2D visual representation of the sound's frequency content over time.
- These spectrograms are resized to a uniform shape (128x128) and normalized for consistent input to the model.
- The spectrograms are treated like grayscale images and passed through a **CNN**, which automatically learns spatial patterns and features relevant for classification.
- The model is trained to distinguish between the 10 sound classes using labeled data and is evaluated on unseen test samples.
- This approach applies **computer vision techniques** to solve an **audio classification** problem by transforming sound into images.

## Requirements

Install the necessary Python libraries using pip:

```bash
pip install numpy pandas librosa opencv-python tqdm scikit-learn tensorflow matplotlib seaborn
```

This project is done for educational purposes only
