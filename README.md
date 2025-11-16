# EmotionDetection
This section provides the essential descriptive framework for a foundational emotion detection system, focusing on the six universally recognized basic human emotions. These definitions are crucial for data labeling and model training.
This project is built upon the FER-2013 (Facial Expression Recognition 2013) Dataset.

Data Source: The core data is derived from the $\text{FER-2013.csv}$ file, a standard benchmark for emotion recognition, containing approximately 35,000 samples.

Data Format: Each entry in the dataset provides a grayscale image ($48 \times 48$ pixels) represented as a string of $2304$ space-separated pixel values, paired with its corresponding ground-truth label (one of seven universal emotions: Angry, Disgust, Fear, Happy, Sad, Surprise, Neutral).

Project Goal: The primary objective is to train a Convolutional Neural Network (CNN) capable of accurately learning the subtle features of human facial expressions from this challenging, low-resolution data. The final output is a robust system deployed for real-time emotion classification on live video input.
