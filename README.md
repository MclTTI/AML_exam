# AML_exam
Repo for the AML exam material

Source of the original code https://github.com/eric-moreno/Anomaly-Detection-Autoencoder

The used dataset is synthetic and contains both realistic LIGO *noise events* and *injection events*, in which a GW waveform is superimposed on the synthetic instrumental noise.
It has been generated with the program available at this repo https://github.com/timothygebhard/ggwd

Link to a minimal (working, used for training on Colab) dataset: https://drive.google.com/file/d/18raqTXI-BLZYGVggGUc6pcQ9NggtEykK/view?usp=sharing

**train.ipynb** and **eval.ipynb** contain the code (and a few comments) to train and test the AEs, respectively.
(NB: train.ipynb is blank since the training has been performed on Colab. Here the link to one of the used notebook https://colab.research.google.com/drive/11bZVRvpJskp8AUb-ncRuBQTIcfC8GQgY?usp=sharing)

The **output** directory contains some output example.
