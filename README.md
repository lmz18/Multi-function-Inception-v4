# Multi-function-Inception-v4

An example of a Multi-function Inception-v4 model is created.
There are 4 python files, and main.py is the file to run.

All together, from these scripts, several multi-function Inception-v4 and several single-function Inception-v4 models are created, trained, and tested on a dataset. For evaluation, training accuracy and test accuracy are calculated for all CNN models.

Currently, the activation functions are randomly chosen for all neurons in a conv block from a set of activation functions defined by the user.

To run the code:
```
python3 main.py
```

Citations:
1) Google Inception v4:

@article{journals/corr/SzegedyIV16,
  added-at = {2016-03-01T00:00:00.000+0100},
  author = {Szegedy, Christian and Ioffe, Sergey and Vanhoucke, Vincent},
  biburl = {https://www.bibsonomy.org/bibtex/23ec63c12997faa69b9a3b9033eb24a37/dblp},
  ee = {http://arxiv.org/abs/1602.07261},
  interhash = {aea48078344599b4468bc255bdcce275},
  intrahash = {3ec63c12997faa69b9a3b9033eb24a37},
  journal = {CoRR},
  keywords = {dblp},
  timestamp = {2016-03-02T11:36:05.000+0100},
  title = {Inception-v4, Inception-ResNet and the Impact of Residual Connections on Learning.},
  url = {http://dblp.uni-trier.de/db/journals/corr/corr1602.html#SzegedyIV16},
  volume = {abs/1602.07261},
  year = 2016
}




2) Keras:

@misc{chollet2015keras,
  title={Keras},
  author={Chollet, Fran\c{c}ois and others},
  year={2015},
  howpublished={\url{https://keras.io}},
}
