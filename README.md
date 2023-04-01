# Name or Not
## Introduction
This "Name or Not" model uses Tensorflow to determine whether or not
a given phrase is the name of a person, or not. It was trained on individual
words and thus functions the best on individual words.
## Usage
### Engineering
If you want to play around with the model construction, you will have to:
  1. Download Tensorflow
  2. Download gtts(for text-to-speech--not required, but if you choose not to use it
    be sure to delete the import and its usage in the Jupyter notebook)
  3. Download the dataset for the names at https://pypi.org/project/names-dataset/
    into the project folder. In particular, the "curate" folder should be listed directly
    under the project folder so that it may be referenced from the Jupyter notebook through:
    ```"./curate"```.
### Utility
On the other hand, if you just want to use the model, you will have to:
  1. Download Tensorflow
  2. Load either the weight1 or weight2 weight sets(make
    sure to check the model architecture as listed in the Jupyter notebook)
  3. Use model.predict() as it fits your needs.
