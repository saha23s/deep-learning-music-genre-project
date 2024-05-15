# Music Genre Classification: comparing impact of feature extraction on the model prediction

Presentation: https://docs.google.com/presentation/d/1HK2uQfzn6I3rcOjczdGtCS_dwhbFI-E17oWCMdf1ip4/edit?usp=sharing [On Progress]
Author: Sulagna Saha

Instructions on how to run the code:
1. Download the GTZAN dataset from the following link: https://www.kaggle.com/datasets/andradaolteanu/gtzan-dataset-music-genre-classification
2. Extract the dataset and place it in the 'Data' folder in the same directory as the notebook "MusicGenreClassification_Model_Creation.ipynb"
3. Run the code cells in the notebook to extract features from raw audio files and train the models.
4. The code cells are divided into two parts: Feature Extraction from Scratch and Feature Extraction Using Pre-trained VGGish Model.
5. The Feature Extraction from Scratch part extracts features from raw audio files and trains the models using LSTM, CNN, and Transformer architectures.
6. The Feature Extraction Using Pre-trained VGGish Model part extracts features using the pre-trained VGGish model and trains the models using LSTM, CNN, and Transformer architectures.
7. The results of the models are displayed at the end of each part.

Abstract:

This project proposes the implementation of a deep learning model for music genre classification, mainly to observe how proper feature extraction can impact the model accuracy. The task of music genre classification, as defined by Tzanetakis and Cook, aims to accurately predict the genre of a given piece of music. Such a task could enhance various music-related applications, including music recommendation systems and search engines, which rely on precise genre labeling. Accurate genre classification could also assist in music analysis and understanding the characteristics of different music genres. This project was specifically designed to 

- Extracting features from scratch and also using a pre-trained model.
  
- Using current deep learning techniques: LSTM, CNN and Transformer model and comparing their predictions


References:

[1] GTZAN Dataset (https://datasets.activeloop.ai/docs/ml/datasets/gtzan-genre-dataset/)

[2] VGGish Model (https://apple.github.io/turicreate/docs/userguide/sound_classifier/how-it-works.html)

[3] Bhavesh Mittal. "Music Genre Classification using VGGish CNN." (https://www.kaggle.com/code/bhaveshmittal/music-genre-classification-vggish-cnn/notebook)

[4] T. L. Li, A. B. Chan, and A. Chun, “Automatic musical pattern feature extraction using convolutional neural network,” in Proc. Int. Conf. Data Mining and Applications, 2010

[5] D. Mingwen, “Convolutional Neural Network Achieves Human-level Accuracy in Music Genre Classification”, 2018

[6] Tzanetakis, G., & Cook, P. (2002). Musical genre classification of audio signals. IEEE Transactions on speech and audio processing. (2006)

[7] Automatic genre classification of music content: a survey. IEEE Signal Processing Magazine. Choi, K., Fazekas, G., Sandler, M., & Cho, K. (2017)

[8] Convolutional recurrent neural networks for music classification. IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP) (2017)

[9] Dieleman, S., & Schrauwen, B. End-to-end learning for music audio. 2014 IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP) (2014)




