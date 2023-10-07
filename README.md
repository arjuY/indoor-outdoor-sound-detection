# indoor outdoor sound detection

The aim of this project is to build a machine learning pipeline that takes as an input an audio segment and predicts whether the audio segment has been recorded indoors or outdoors.

# Dataset
The dataset used in this project is the publicly available MLEnd London Sounds dataset (https://www.kaggle.com/datasets/jesusrequena/mlend-london-sounds). The MLEnd London Sounds dataset consists of more than 2,500 audio files recorded across London, at iconic places such The British Museum, Covent Garden and The Southbank Centre.

# Model

The models trained for this classification problem are SVM and Logistic Regression. The performance of both the models is compared on this dataset. Logistic regression and support vector machines are both supervised machine learning algorithms. They both are used to solve classification problems.
It was found that SVM seems to perform better for this particular dataset and achieves 75% accuracy on test dataset.

# Requirements
Python 3.x  librosa
