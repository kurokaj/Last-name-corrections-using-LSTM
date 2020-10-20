# Last-name-corrections-using-LSTM
The purpose of this notebook is to train a recurrent neural network model that suggests corrections to given finnish lastnames. If the input last name seems correct, no advice is given.  

## Data
The data is collected from the https://www.avoindata.fi/data/en_GB/dataset/none. 

"""
The Population Information System has been extracted from the names and surnames of names and surnames in the Population Information System. For privacy reasons, the underlings of less than 5 and the family names of less than 20 are not included in the lists.
"""

## Model
The Encoder-decoder architecture uses LSTM- layers to capture the dependency of following letters in each name.  

## Results
