Text LSTM Autoencoder
===

Usage
===

* ``prepare-data.py``: prepare data for training
  $ python3 src/prepare-data.py <path to train input> <path to valid summaries> <path to output dir>

* ``train-autoencoder.py``: train a new autoencoder model
  $ python3 src/train-autoencoder.py <...>/autoencoder/model <..>/autoencoder/data/output/vocabulary.txt <..>/autoencoder/data/output/train-data.npz <..>/autoencoder/data/output/valid-data.npz
