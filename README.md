# Speech Emotion Recognition (SER) using the EMOVOME database
This repository contains the Python implementation of the article: "EMOVOME Database: Advancing Emotion Recognition in Speech Beyond Staged Scenarios".

## Citation
If you use this code in your research, please cite our work as follows:

> L. Gómez-Zaragozá, R. del Amor, M. Castro-Bleda, V. Naranjo, M. Alcañiz Raya and J. Marín-Morales, "EMOVOME Database: Advancing Emotion Recognition in Speech Beyond Staged Scenarios", 2024. [https://arxiv.org/abs/2403.02167](https://arxiv.org/abs/2403.02167)


```
@misc{gomez2024,
  title={EMOVOME Database: Advancing Emotion Recognition in Speech Beyond Staged Scenarios},
  author={Lucía Gómez-Zaragozá and Rocío del Amor and María José Castro-Bleda and Valery Naranjo and Mariano Alcañiz Raya and Javier Marín-Morales},
  year={2024},
  eprint={2403.02167},
  archivePrefix={arXiv},
}
```

## Files and folders
* 1_extract_features: folder with the following sub-folders
  * 1_eGeMAPS_features: code to extract the eGeMAPS features 
  * 2_speech_embeddings: code to extract the speech embeddings using different pre-trained models
  * 3_combine_eGeMAPS_embeddings: code to combine the eGeMAPS features and the speech embeddings
* 2_run_SER_models: folder with the following jupyter notebooks
  * baseline_egemaps.ipynb: code to implement the baseline models based on eGeMAPS
  * model_embeddings.ipynb: code to run the models using the embeddings and/or their combination with eGeMAPS


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

To run the Jupyter notebooks, ensure Jupyter is installed in your environment. You can install it using: 

```bash
pip install jupyter
```

You can then open and run the Jupyter notebooks with the following command:

```bash
jupyter notebook my_notebook.ipynb
```



