# learning-deep-learning

# Course program

* Basics of deep learning
  1. Introduction, backpropagation algorithm
  2. Empirical risk minimization, standard loss functions, linear classification, stochastic optimizers
* Computer vision
  1. Convolutional networks (ConvNets), classifying images. **Homework**
  2. "Deep" computer vision beyond classification: Verification tasks, object detection architectures, semantic segmentation
  3. Generation networks
    ```
      -- Article deadline: Journal club --
    ```
  4. Generation: AE, VAE, GAN. **Homework**
* Natural language processing
  1. Word embeddings, word2vec and other variants, convolutional networks for natural language
  2. RNN, LSTM. **Homework**
  3. Sequence2sequence, attention, transformers and other advanced techniques
  
  ```
  -- Article deadline: present current results --
  ```
* Deep reinfocrement learning. **Homework**
* Adverserial examples, MobileNet, distillation, dark knowledge

  ```
  -- Artice deadline: present final results --
  ```

# Classes

## Lecture 1. (6.02.2019)
**Lecture** Introduction, backpropagation algorithm [.pptx](https://drive.google.com/open?id=12-E7YoEZiDBPl7ZGI5KFQwwiPIHHuVDi), [.pdf](https://drive.google.com/open?id=1VmZ3VL9m9v0In_5utGlS3KKd8DIgAfqB)

**Seminar** Introduction to pytorch.

**Homework:** Fill [Seminar 1 notebook](01_intro/seminar_pytorch_vs_numpy.ipynb) and send it to AnyTask until 13.02.19 (8:00)

## Lecture 2. (13.02.2019)
**Lecture** Optimization for Deep Learning [.pptx](https://drive.google.com/open?id=19e-rf_b1jBT_lv_aOkObvYXM3nbSxhG4), [.pdf](https://drive.google.com/open?id=1GwFNLKiA-lPVX88cc6uWNFkunLcirgs6).

**Seminar** High level pytorch.

**Homework:**
* Please read good logloss explanation here: https://dyakonov.org/2018/03/12/логистическая-функция-ошибки/
* Fill [Seminar 2 notebook](02_basic_nn/seminar_high_level_pytorch.ipynb) and send it to AnyTask until 20.02.19 (8:00)


## Lecture 3. (20.02.2010)
**Lecture** Convolutional Networks. [.pptx](https://drive.google.com/open?id=1rltJSToDGCI37wWVC3IGRLUUKYixRK6J), [.pdf](https://drive.google.com/open?id=1vi29F7q44bvhKXtZ-MQsjPQ7CkNQEQuE)

**Seminar** Cifar10 finetuning.

**Homework:**
* Fill Seminar 3 notebook
* **HW1** Cifar10 classification.


## Lecture 4. (27.02.2019)
**Lecture** Convolutional Networks in Computer Vision (segmentation, detection, verification) [.pptx](https://drive.google.com/open?id=1aAW22FkAWMt6ZMiEbGtHrX1S0XLY-H72), [.pdf](https://drive.google.com/open?id=16XnW4KheNSuFjjHce6M01qfrxe0NGmnl)

**Seminar** Dense prediction.

**Homework:**
* Fill Seminar 4 notebook
* Find an article for journal club (13.03).

## Lecture 5. (06.03.2019)
**Lecture** Generative Convolutional Networks [.pptx](https://drive.google.com/file/d/1PXWn-0G3OLM24yfQWiXm-t_fj8lIQNZ0/view?usp=sharing), [.pdf](https://drive.google.com/file/d/1BBXqao38645yTlRTtYLrnmXoylwY0AjP/view?usp=sharing)

**Seminar** Neural Style Transfer.

**Homework:**
* Fill Seminar 5 notebook
* Find an article for journal club (13.03).

## Journal club. (13.03.2019)

## Lecture 6. (20.03.2019)
**Lecture** Autoencoders and GANs. [.pptx](https://drive.google.com/open?id=1LUL1uUahloUKUrLYAMvNuIErX9BakGz9), [.pdf](https://drive.google.com/open?id=1trIvsIRuXBbONyHPUCyVjuzb34HIjIv1)

Useful link – VAE: https://neurohive.io/ru/osnovy-data-science/variacionnyj-avtojenkoder-vae/

**Seminar** Fashion-MNIST GAN

**Homework:**
* Fill Seminar 6 notebook

## Lecture 7. (27.03.2019)
**Lecture** NLP intro, ConvNets for NLP, Word embeddings.

**Seminar** w2v

**Homework:**
* Fill Seminar 7 notebook

## Lecture 8. (3.04.2019)
**Lecture** RNN, LSTM. [.pptx](https://drive.google.com/open?id=1A0e0My9G_jMxUadYU-7SDl0spWyigK8g), [.pdf](https://drive.google.com/open?id=1MxqvNJSGOwHZlPC9MnLSklxpZNhLnQaV)

**Seminar** Char RNN

**Homework:**
* LSTM – http://colah.github.io/posts/2015-08-Understanding-LSTMs/
* То же на русском – https://habr.com/ru/company/wunderfund/blog/331310/
* Attention – https://www.youtube.com/watch?v=k63pDjKV3Ew
* Fill Seminar 8 notebook
* **HW3** Image captioning

## Lecture 9. (10.04.2019)
**Lecture** Speech2Text. Seq2seq. Transformer [.pptx](https://drive.google.com/open?id=1vBULDrEats24Kn01C_mHqfIu-CuLcqQx), [.pdf](https://drive.google.com/open?id=1N-VYRjHnrldBDZ3Qcb9OvECRDLd-iBq6)

**Seminar** Seq2seq

**Homework:**
* Fill Seminar 9 notebook
* Upload intermediate results of course work

# Сourse evaluation criteria

* 10 seminar tasks: 4 points each
* 4 homeworks: 10 points each
* 1 article implementation + journal club. 5 (journal club) + 5 (current results) + 10 (final results) points

Submissions missed deadlines are estimated at half points maximum.

Total sum is 100 points. Course grades:
* 80 points -> 8/10
* 50 points -> 5/10
* 30 points -> 3/10
