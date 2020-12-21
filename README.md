# google_speech_command_recognition
A convolutional neural network recognizing 31 classes from the Google Speech Command Dataset

## Prerequisites
* Mac 10.16.6+
* Python 3.8+
* Tensorflow 2.3+
* Librosa 0.8.0+
* Jupyter Notebook 6.1.5+
* Matplotlib 3.3.3+


## How to run this notebook
1. In the top-level directory, download the [Google Speech Command Dataset](http://download.tensorflow.org/data/speech_commands_v0.01.tar.gz) from [this blog post](https://ai.googleblog.com/2017/08/launching-speech-commands-dataset.html)
1. Rename the dataset folder to "dataset"
1. Run cells in order:
    1. A process to extract the dataset features will run, which could take up to an hour
    1. This will be stored as data.json in the top-level directory
    1. The notebook will continue by building a CNN from this data
1. A prediction service will run to test the model.
1. Results will be logged and displayed in Tensorboard
