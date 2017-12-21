# TwitterSentiment
Repository for CS-433 Machine Learning project 2.
The task chosen is the [Twitter text classification task.](https://www.kaggle.com/c/epfml17-text)

Team members: Adam Kozak, Tarmo Nurmi, Matthias Tsai.

Kaggle team: KozakNurmiTsai.

# Requirements:
Besides common Python libraries (numpy etc.).

Running the data preprocessing requires:
- [Hunspell](https://pypi.python.org/pypi/hunspell) v. 0.5.0

Running the embedding and model fitting requires:
- [Keras](https://github.com/fchollet/keras) (Newest version on 2017-12-21)
- [Gensim](https://pypi.python.org/pypi/gensim) v. 3.2.0

# Running

To run the pipeline, the user **the user needs to get all the files at https://drive.switch.ch/index.php/s/B3GW73fRf8Ou3Js and add them in the main code directory.**

To run, simply run the **run.py** file. Every file from the previous link should be in the same folder as run.py.

The training time for the full pipeline is about **5 hours** without utilizing a GPU.
