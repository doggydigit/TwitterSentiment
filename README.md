# TwitterSentiment
Repository for CS-433 Machine Learning project 2.
The task chosen is the [Twitter text classification task.](https://www.kaggle.com/c/epfml17-text)

Team members: Adam Kozak, Tarmo Nurmi, Matthias Tsai.

Kaggle team: ???.

# Requirements:
Besides common Python libraries (numpy etc.).

Running the data preprocessing requires:
- [Hunspell](https://pypi.python.org/pypi/hunspell) v. 0.5.0
- Normalization dictionaries:
  - http://www.hlt.utdallas.edu/~yangl/data/Text_Norm_Data_Release_Fei_Liu/
  - http://people.eng.unimelb.edu.au/tbaldwin/etc/emnlp2012-lexnorm.tgz
  - http://luululu.com/tweet/typo-corpus-r1.txt

Running the embedding and model fitting requires:
- [Keras](https://github.com/fchollet/keras) (Newest version on 2017-12-21)
- [Gensim](https://pypi.python.org/pypi/gensim) v. 3.2.0
