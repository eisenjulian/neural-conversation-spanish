# Neural Conversation Spanish
A neural conversation model implementation in Spanish built with Tensor Flow

Based on [this paper](https://arxiv.org/abs/1506.05869) this model uses movie subtitles in Spanish from www.opensubtitles.org 
as well a pre-trained word vectors from [FastText](https://github.com/facebookresearch/fastText)
to train a LSTM network in TensorFlow to achieve a conversation agent.

### Set Up
Python installation with TensorFlow. Check out https://www.tensorflow.org/install/
Download the subtitle data from opensubtitles.org from [here](http://opus.lingfil.uu.se/download.php?f=OpenSubtitles2016/es.raw.tar.gz). It may take a while...

### Train
```
python translate.py
```

### Test
```
python translate.py --decode
> ¿Coómo estas?
> Bien
```
