
# Advanced DL course Assignment II
Contributors: Adi Dokhan & Lilac Muhanna

## Project Overview
This project develops a text classification model to determine whether a given piece of dialogue comes from "Friends" or "Seinfeld". We utilized Natural Language Processing techniques to process and vectorize dialogue data from 70,405 lines of scripts. The model aims to accurately classify dialogues into their respective TV shows based on textual content alone.

## Models Developed
Logistic Regression: Served as a baseline for comparison.
Deep Learning Model (Neural Network): Used an embedding layer followed by convolutional and dense layers.

## Results
Best Model: Neural Network  
Validation Accuracy: 84.38%  
Test Accuracy: 83.39%  
Test AUC: 0.921  
The neural network provided the best performance, showcasing the importance of deep learning in handling complex patterns in text data.

## Conclusion
The developed model effectively distinguishes between dialogues from two culturally iconic sitcoms. Future work could explore more complex architectures and additional textual features to further enhance performance.

## Libraries Used
Pandas, NumPy, Matplotlib, Seaborn, TensorFlow (Keras), Scikit-Learn, NLTK
![image](https://github.com/LilacMuhanna/Sitcom-Line-Classifier-Seinfeld-vs.-Friends/assets/155223486/4262283f-03f7-43b5-a771-bc1a94ed2640)
