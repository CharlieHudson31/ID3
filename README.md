# ID3
This program predicts a binary class from training data. It also evaluates the accuracy of the prediction from test data.
Usage: python3 id3.py training_data test_data model_file.txt
Data:
    There are 3 folders with data in CSV format. They include training and test data.
Model:
    The final decision tree can be compared to the example models. Note the output tree may not be the exact same as the example trees, because when their are multiple candidates for an attribute with the max gain, an arbituary decision is made for selection.