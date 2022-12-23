# Statoil-C-CORE-Iceberg-Classifier-Challenge
Ship or iceberg, can you decide from space?
kaggle dataset : https://www.kaggle.com/competitions/statoil-iceberg-classifier-challenge/overview

my kaggle profile : https://www.kaggle.com/semjinwu
my solution
1. tranfrom band values to image shape(75,75,3) (no augmentation)
2. use CNN by create convolution layer use ativation function 'relu' and output layer use 'sigmoid'
3. train model with loss='binary_crossentropy' and ADAM optimizer
4. predict with test data amnd make submission file .csv
