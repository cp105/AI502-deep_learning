# AI502 Deep Learninng - KAIST academic year 2019/20 spring semester

This course included several basic and intermediate concepts and contents regarding state of the art deep learning.
Some of the covered topics included:
  - pytorch library
  - basics of DL including transfer learning in DL, deep double descent, etc..
  - CNN
  - RNN theory, LSTM, GRU
  - attention and attention mechanism
  - Seq2seq models, transformer architecture, BERT, GPT-2, etc..
  - Adversarial learning
  - generative models, VAE, GAN, conditional GAN
  - short intro on energy based models

# Repository contents

  - Homeworks, including topics like pytorch library for ANNs, CNNs for image classification, RNN models such as LSTM and GRU, generative models such as vanilla VAE.
  - Midterm survey paper
  - Final term survey paper
  - Final individual project consisting in the .ipynb file, and final report.

## Midterm survey papers

Papers included in the survey paper:
  - Smith, Samuel L., et al. "Don’t decay the learning rate, increase the batch size."
International Conference on Learning Representations (2018).
  - Liu, Liyuan, et al. "On the variance of the adaptive learning rate and beyond."
International Conference on Learning Representations (2020).
  - Sandler, Mark, et al. "Mobilenetv2: Inverted residuals and linear bottlenecks."
Proceedings of the IEEE conference on computer vision and pattern recognition (2018).
  - Summers, Cecilia, and Michael J. Dinneen. "Four Things Everyone Should Know to
Improve Batch Normalization." International Conference on Learning Representations
(2020).

## Finalterm survey papers

Papers included in the survey paper:
  - Cho, Kyunghyun, et al. "Learning phrase representations using RNN encoder-decoder for
statistical machine translation."
Proceedings of the 2014 Conference on Empirical Methods in Natural Language Processing.
  - Rifai, Salah, et al. "Contractive auto-encoders: Explicit invariance during feature extraction."
Proceedings of the 28th International Conference on Machine Learning (2011).
  - Razavi, Ali, et al. "Generating diverse high-fidelity images with VQ-VAE-2."
Advances in Neural Information Processing Systems (2019).
  - Arjovsky, Martin, et al. "Wasserstein GAN."

## Final individual project - “Tweet Sentiment Extraction” Kaggle challenge

In the ./final_project folder.
The “Tweet Sentiment Extraction” dataset https://www.kaggle.com/c/tweet-sentiment-extraction
consists in a collection of 27481 tweets, labeled with a sentiment (positive, negative or neutral) and
characterized by a contiguous portion of the former tweet which is supposed to lead to the labeled
sentiment. The goal of this Kaggle competition is to construct a model which can look at the labeled
sentiment for a given tweet and figure out what word or phrase best supports it.
The evaluation metric for the challenge consists in the jaccard metric, which is provided in the
challenge page, and which is supposed to measure the IoU (Intersection over Union) of the ground
truth extracted tweet with respect to the one which is determined with our trained model.
In the report we also analyze a range of possible methods which could be adopted to solve the given task.

