Speech carries robust information, such as emotion and cognitive state, that is readily accessible to the human ear. However, because audio is an unstructured form of data, this information must be methodically extracted to be accessible for machine learning. If done successfully, such data can be used for voice technology with great accessibility and a minimal learning curve. As a proof of concept, could I use machine learning to classify a speaker's sex and emotion?

The following is to let the reader know which parts to prioritize when evaluating my work:
- Part 1 is the most informative and well-documented. I attempted to explain all my thought processes when learning how to analyze audio data. I originally considered using four different datasets, but had to choose one due to the time constraint. I decided on the most accessible and well-balanced dataset.
- Parts 2a to 2e contain all the different approaches I tried when building classical machine learning models. 
	- Part 2a is the most well-documented.
	- Part 2b is only subtly different from part 2a, and this contains the best-performing models. These are the models I used in part 5.
	- Parts 2c, 2d, and 2e are not as well-documented due to my attempt to quickly explore other solutions, and the models in these parts performed poorly in comparison.
- Part 3 contains all the convolutional neural networks I tried. These did not perform as well as the classical models I built in parts 2a and 2b.
- Part 4 is where I tested my best-performing models on a new dataset. Unfortunately, they did not perform well and I wrote some possible explanations.
- Part 5 is the notebook I presented on demo day along with the slides. This is what I used to record the visitors' voices and have my models predict their genders and emotions.

Here is the link to the slides I presented on demo day: https://prezi.com/p/trzqgvimdrtz

These are the references I used to study how to analyze audio data:
- https://towardsdatascience.com/getting-to-know-the-mel-spectrogram-31bca3e2d9d0
- https://www.youtube.com/watch?v=spUNpyF58BY
- https://www.khanacademy.org/science/electrical-engineering/ee-signals/ee-fourier-series/v/ee-fourier-series-intro
- https://opensource.com/article/19/9/audio-processing-machine-learning-python
- https://www.kaggle.com/ejlok1/kernels
- https://github.com/MITESHPUTHRANNEU/Speech-Emotion-Analyzer
- https://www.kaggle.com/fizzbuzz/beginner-s-guide-to-audio-data
- https://medium.com/prathena/the-dummys-guide-to-mfcc-aceab2450fd
- http://practicalcryptography.com/miscellaneous/machine-learning/guide-mel-frequency-cepstral-coefficients-mfccs
- https://medium.com/x8-the-ai-community/audio-classification-using-cnn-coding-example-f9cbd272269e
- https://towardsdatascience.com/music-genre-classification-with-python-c714d032f0d8
