The below list includes various resources comprising of NLP and image-captioning tutorials, papers and implementations of the papers as well as few blogs that would help in understanding the papers.

<<<<<<< HEAD
I. pytorch tutorials 
------------------------------------
=======
*Note: Most of the tutorials and implementations below are in pytorch.*
>>>>>>> 07641a11205f5331aa218b8fec931213d9d46211

Pytorch Tutorials 
------------------------------------
Basics:

- [Getting Started-0](https://pytorch.org/tutorials/beginner/deep_learning_nlp_tutorial.html)

- [Getting Started-1](https://github.com/hunkim/PyTorchZeroToAll)

- [Classifying Names with Character-Level RNN](https://pytorch.org/tutorials/intermediate/char_rnn_classification_tutorial.html#sphx-glr-intermediate-char-rnn-classification-tutorial-py)

- [Generating Names with Character-Level RNN](https://pytorch.org/tutorials/intermediate/char_rnn_generation_tutorial.html)

- [Translation with a Seq2seq network and Attention](https://pytorch.org/tutorials/intermediate/seq2seq_translation_tutorial.html)

For understanding the working of sequence 2 sequence networks 
I would reccomend to atleast go over these papers : 

(a) [Sequence to Sequence Learning with Neural Networks](https://arxiv.org/pdf/1409.3215.pdf)

(b) [NEURAL MACHINE TRANSLATION BY JOINTLY LEARNING  TO ALIGN AND TRANSLATE](https://arxiv.org/pdf/1409.0473.pdf)

(c) [Effective Approaches to Attention-based Neural Machine Translation](https://arxiv.org/pdf/1508.04025.pdf)

- [Understanding and visualizing pytorch lstm batching](https://github.com/ngarneau/understanding-pytorch-batching-lstm)

- [Implementations of different LSTM Cells](https://github.com/Atcold/pytorch-CortexNet)
*I had a short discussion with AtCold. He seemed very helpful.*

- https://github.com/MaximumEntropy/Seq2Seq-PyTorch -- seems to be a very good code with all implementations of the beam search and all. He has also provided the benchmark results which seems to be quite good.

- https://github.com/AuCson/PyTorch-Batch-Attention-Seq2seq -- this implementation handles batched inputs, and that it implements a slightly different attention mechanism. the author has got 10X speed improvements ! he has said that the code seems to handle well his personal projects.



Image Caption generation
------------------------------------
1. Paper : [Show and Tell: A Neural Image Caption Generator](https://arxiv.org/pdf/1411.4555.pdf)
Implementation: https://github.com/yunjey/pytorch-tutorial/tree/master/tutorials/03-advanced/image_captioning

2. Paper : [Show, Attend and Tell: Neural Image Caption Generation with Visual Attention](https://arxiv.org/pdf/1502.03044.pdf)
Implemenatation: https://github.com/sgrvinod/a-PyTorch-Tutorial-to-Image-Captioning


II. For image to caption generation
------------------------------------
Show and Tell
-------------
[1] https://github.com/amundv/kth-sml-project

[2] https://github.com/muggin/show-and-tell

[3] https://github.com/tensorflow/models/tree/master/research/im2txt -- official codes from tensorflow !!

Show Attend and Tell
-------------------------
[1] https://github.com/parksunwoo/show_attend_and_tell_pytorch

[2] https://github.com/sgrvinod/a-PyTorch-Tutorial-to-Image-Captioning

[3] https://github.com/DeepRNN/image_captioning

[4] https://github.com/yunjey/show-attend-and-tell

Knowing When to Look
----------------------
[1] https://github.com/yufengm/Adaptive

[2] https://github.com/metrofun/AdaptiveAttention

[3] https://github.com/jiasenlu/AdaptiveAttention

[4] https://github.com/amaiasalvador/imcap_keras

[5] https://github.com/yunjey/knowing-when-to-look

Some Codebases
----------------

[1] https://github.com/ruotianluo/ImageCaptioning.pytorch

[2] https://github.com/yunjey/pytorch-tutorial/tree/master/tutorials/03-advanced/image_captioning

[3] https://github.com/ruotianluo/self-critical.pytorch

[4] https://github.com/yudi09/pytorch-image-captioning

[5] https://github.com/luckytoilet/csc2548-caption-rnn

[6] https://github.com/yashk2810/Image-Captioning


III. Some blogs and papers to read 
-----------------------------

[1] Show and Tell: A Neural Image Caption Generator -- https://arxiv.org/pdf/1411.4555.pdf

[2] Show, Attend and Tell: Neural Image Caption Generation with Visual Attention -- https://arxiv.org/pdf/1502.03044.pdf

https://medium.com/@ahmdtaha/show-attend-and-tell-neural-image-caption-generation-with-visual-attention-9772ca582be5

https://medium.freecodecamp.org/building-an-image-caption-generator-with-deep-learning-in-tensorflow-a142722e9b1f

[3] https://blog.heuritech.com/2016/01/20/attention-mechanism/

[4] Knowing When to Look: Adaptive Attention via A Visual Sentinel for Image Captioning -- https://arxiv.org/pdf/1612.01887.pdf

[5] Self-critical Sequence Training for Image Captioning -- https://arxiv.org/pdf/1612.00563.pdf

P.S. NOTE THAT I HAVE NOT READ THIS PAPER. THIS PAPER SEEMS TO HAVE BEEN WRITTEN USING THE CONCEPTS OF RE-INFORCEMENT LEARNING!

[6] Bottom-Up and Top-Down Attention for Image Captioning and Visual Question Answering -- https://arxiv.org/pdf/1707.07998.pdf

<<<<<<< HEAD



IV. For using the word2vec models
=======
For using the word2vec models
>>>>>>> 07641a11205f5331aa218b8fec931213d9d46211
------------------------------------

http://mccormickml.com/2016/04/12/googles-pretrained-word2vec-model-in-python/

https://stats.stackexchange.com/questions/267169/how-to-use-pre-trained-word2vec-model

http://ahogrammer.com/2017/01/20/the-list-of-pretrained-word-embeddings/

https://machinelearningmastery.com/develop-word-embeddings-python-gensim/

Additional resources:
----------------------

- https://github.com/eladhoffer/seq2seq.pytorch

- https://github.com/eladhoffer/captionGen

- https://github.com/keon/seq2seq
