# EEG_Emotion_Recognition


### Software and Tools Requirements

1. [Sklearn](https://scikit-learn.org/stable/)
2. [Pandas](https://pandas.pydata.org/)
3. [Numpy](https://numpy.org/)
4. [Scipy](https://scipy.org/)
5. [MNE](https://mne.tools/stable/index.html)
6. [Pywt](https://pywavelets.readthedocs.io/en/latest/)
7. [Matplotlib](https://matplotlib.org/)

### Train, Validation, and Test data information
1. We have used 10 fold cross validation to find out the best split of the training data. 
2. We find out that split-0 gave us the best split with 0.2555 validation Accuracy. So we have used split-0 for our model training.
3. We have putin all the split arrays in the IndexesFrom10Fold folder. But we have selected train_0 and test_0 indexes arrays for our model training.
4. Training Raw data and labels array are available in the TrainRawDataArray folder.
5. Validation Rawa data and labels array are available in the ValidationRawDataArray folder.
6. Test Raw data array is available in the TestRawDataArray folder.

### How to run the Code
Just donload the complete repository and put in the anaconda jupyter home directory. In the fikes there is .ipynb file with name "ModelFile.ipynb". Open the ModelFile,ipynb in the jupyter environment an run each cell one by one.