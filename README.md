# Video Captioning For Arabic Sign Language Recognition At Sentence Level

## Table of Contents
1. [Desription](#description)
2. [Dataset](#dataset)
3. [Installation and Usage](#installation-usage)

## Description <a name="description"></a>
An encoder-decoder deep learning model (with/without attention mechanism) where the input is an arabic sign-language video and the output is its translation in text format. 
> **Note:** For a detailed model architecture and preprocesing, refer *Video Captioning.ipynb* file.

## Dataset <a name="dataset"></a>
The dataset consists of 
1. Total number of video samples are 534.
1. 10 different sentences performed by three signers.
2. Each video sample is already normalized to 80 frames.

## Installation and Usage <a name="installation-usage"></a>
  - Requirements
    - `python >= 3.6`
  - `git clone https://github.com/AI-14/video-captioning-for-arabic-sign-language-recognition-at-sentence-level.git` - clones the repository
  - `cd video-captioning-for-arabic-sign-language-recognition-at-sentence-level`
  - `py -m venv yourVenvName` - creates a virtual environment
  - `pip install -r requirements.txt` - installs all modules
  - open the `.ipynb` file
