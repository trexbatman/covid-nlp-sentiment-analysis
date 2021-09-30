This folder contains all files required for reproducing the results of the paper "Are BERT-based models really king in domain specific scenarios? A Twitter COVID-19 Sentiment Analysis Case Study".

To reproduce the results:
1) Make sure you have a version of Python installed, such as Anaconda.
2) Open the RNN_and_RF_models.ipynb file and BERT_based_model.ipynb files and run cells that install the packages contained in the requirements.txt file.

The folder also contain:
1) 'figures' folder with pictures included in the paper or generated as part of the ipynb files.
2) 'saved_model' folder that contains all information required for running the RNN-based model without needing to train it again. Instructions on how to do that can be found at: https://www.tensorflow.org/tutorials/keras/save_and_load
3) 'training_1'folder contains the weights for the RNN-based model. Again, further instructions on how to use the files contained in the folder can be found at: https://www.tensorflow.org/tutorials/keras/save_and_load
4) 'random_forest.joblib' contains the Random Forest based model.
5) The 'cardiffnlp' model was not included due to its size (500mb), but it can be easily downloaded with the script BERT_based_model.ipynb.
