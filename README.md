# Speech Emotion Recognition (SER) using the EMOVOME database
This repository contains the Python implementation of the article: "EMOVOME Database: Advancing Emotion Recognizing in Speech Beyond Staged Scenarios".

## Citation
If you use this code in your research, please cite our work as follows:

> L. Gómez-Zaragozá, R. del Amor, M. Castro-Bleda, V. Naranjo, M. Alcañiz Raya and J. Marín-Morales, "EMOVOME Database: Advancing Emotion Recognizing in Speech Beyond Staged Scenarios", 2024. [https://arxiv.org/abs/2403.02167](https://arxiv.org/abs/2403.02167)


```
@misc{gomez2024,
  title={EMOVOME Database: Advancing Emotion Recognizing in Speech Beyond Staged Scenarios},
  author={Lucía Gómez-Zaragozá and Rocío del Amor and María José Castro-Bleda and Valery Naranjo and Mariano Alcañiz Raya and Javier Marín-Morales},
  year={2024},
  eprint={2403.02167},
  archivePrefix={arXiv},
}
```

## Files and folders
* data: description of the ADReSS Challenge data, and instructions on how to obtain it.
* codes: folder with the following jupyter notebooks
  * 1_Automatic Speech Recognition (ASR): transcription of the audio files using different automatic speech recognition models.
  * 2_1_Feature extraction: feature extraction and pause encoding. 
  * 2_2_Machine learning: training the machine learning models based on the previous features.
  * 3_Word embeddings and neural network: pre-trained word embeddings + neural network model training.


## Installation

To ensure a smooth setup, we recommend creating a new virtual environment. Follow these steps:

1. Create a new environment with Conda:

```bash
conda create --name myenv
```
2. Activate the newly created environment:

```bash
conda activate myenv
```

3. Install all dependencies from the requirements.txt file using pip:

```bash
pip3 install -r my_requirements.txt
```

## Usage

You can open and run the code written in Jupyter notebooks with the following command:

```bash
jupyter notebook my_notebook.ipynb
```



