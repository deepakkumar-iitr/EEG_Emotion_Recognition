# EEG_Emotion_Recognition


<!-- ### Software and Tools Requirements -->

<!-- 1. [Sklearn](https://scikit-learn.org/stable/)
2. [Pandas](https://pandas.pydata.org/)
3. [Numpy](https://numpy.org/)
4. [Scipy](https://scipy.org/)
5. [MNE](https://mne.tools/stable/index.html)
6. [Pywt](https://pywavelets.readthedocs.io/en/latest/)
7. [Matplotlib](https://matplotlib.org/) -->

### How to install pywt, mne, scipy, find_peaks, and peak_widths
Just run the below commands in any cell of the jupyter notebook

!pip install pywt

!pip install mne

!pip install scipy

!pip install find_peaks

!pip install peak_widths

### Train, Validation, and Test data information
1. In the given dataset we have 360 samples in the Training data, 180 samples in the Validation data, and 180 samples in the Test data. We have used 10 fold cross validation to find out the best split of the training data. 
2. The best split indexes are saved into numpy arrays named train_0.npy and test_0.npy for train and test data respectively. Both the arrays are available in the "IndexesFrom10Fold" folder. The data corresponding to indexes available in the train_0.npy is finally used to train the model.
4. Training Raw data and label arrays are available in the "TrainRawDataArray" folder.
5. Validation Raw data and label arrays are available in the "ValidationRawDataArray" folder.
6. Test Raw data array is available in the "TestRawDataArray" folder.

All the data folders named above are available at the given google Drive Link:
https://drive.google.com/drive/folders/1dMnwtof4tPlnu27n63vWE3kAJU9P5cB8?usp=sharing

### How to run the Code
1. Clone the given github repository to your local machine.
2. Download all the data folders from the above google drive link and put it in the same directory  where git repository is available. 
3. Open "ModelFile.ipynb" jupyter notebook file and replace the data files paths if needed with their respective locations.  
4. Run all the cells of "ModelFile.ipynb" file and you will be able to reproduce the results.
5. After completion of the running process you will be able to see the validation results and there will be one csv file named "Test_Predictions.csv" in the same working directory, containing the test predictions.