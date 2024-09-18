# Music-Generation-Using-Deep-Learning
This project aimed to develop an AI-driven music ​generation system designed specifically for
creating short audio clips. The system utilized advance AI technologies, including Long
Short-Term Memory (LSTM) networks, Auto-Encoders, and Generative Adversarial Networks
(GANs), to generate short audio clips tailored to specified instrument.

The project leveraged 4-second instrument-specific audio clips from Google’s NSynth dataset as
input to the generator, ensuring the production of high-quality, instrument-specific audio content
for various short-form media applications. Please follow the following to view files 

1. **LSTM.ipynb:** This file utilizes LSTM to predict sequences of spectrograms to
generate spectrograms which are later converted into audio files in ‘.wav’ format.

2. **VAE-gtzan.ipynb:** VAE model for gtzan dataset, https://www.kaggle.com/datasets/andradaolteanu/gtzan-dataset-music-genre-classification.
However later dropped due to insufficient performance/results.

3. **gan.ipynb:** GAN model uses the audio files as input to generator and further evaluates the generated audio using different metrics.

4. **Dataset Link:** https://magenta.tensorflow.org/datasets/nsynth. Downloaded the JSON format.

5. **Project Report.pdf:** Project report that summarizes the results of the utilized models.
