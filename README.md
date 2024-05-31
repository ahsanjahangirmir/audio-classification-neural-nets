# audio-classification-neural-nets
Implementation of Neural Network to classify tens of thousands of audio samples from the AudioMNIST dataset. 

# Audio Signal Processing and Machine Learning with MFCCs and PyTorch

## Overview
In this project, I delve into audio signal processing and machine learning by using Mel-frequency Cepstral Coefficients (MFCCs) to extract features from audio samples. I then utilize these features to train a Neural Network using PyTorch to classify the audio samples.

## About the Dataset

We will use the `AudioMNIST` dataset, which contains tens of thousands of audio samples of people with different accents from various regions of the world, speaking different digits. The dataset is ideal for exploring the intersection of audio processing and machine learning due to its diverse and comprehensive nature.

- **Dataset Composition**: The dataset consists of 60 folders, each representing a different speaker with a distinct accent. 
- **Samples per Folder**: Each folder contains 500 audio files, with each file corresponding to an utterance of a digit from 0 to 9.
- **Total Samples**: This setup results in a vast collection of 30,000 audio samples (60 speakers x 500 samples).

You can access the dataset on [Kaggle](https://www.kaggle.com/datasets/sripaadsrinivasan/audio-mnist).

## Installation and Setup

To run this project, you need to have the following dependencies installed:

- Python 3.6 or higher
- PyTorch
- librosa
- numpy
- pandas
- scikit-learn
- matplotlib

You can install the necessary packages using `pip`:

```bash
pip install torch librosa numpy pandas scikit-learn matplotlib
```

## Contributing
We welcome contributions to improve the project. If you would like to contribute, please fork the repository and submit a pull request with your changes.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Contact
For any questions or inquiries, please contact [25100325@lums.edu.pk](mailto:25100325@lums.edu.pk).
