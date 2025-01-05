
# Genralized image classifcation pipline

This repository provides a complete end-to-end pipeline for multi-class image classification, designed to work with any number of classes and any image resolution. It integrates 12 state-of-the-art and fundamental backbone architectures, including both CNNs and Vision Transformers (ViTs), as well as two customized models tailored for multi-class classification problems.

The pipeline is highly versatile and simplifies the process of building, training, and evaluating classification models. It includes a comprehensive training module that automatically generates detailed summaries, performance metrics, and analysis reports for better insights into model performance.

Key Features:
* Support for Any Dataset: Easily adapt to datasets with varying class counts and resolutions.
* Diverse Architectures: Includes popular CNN backbones and ViT models for flexible experimentation.
* Custom Models: Two specialized models optimized for multi-class classification tasks.
* Comprehensive Training Module: Handles all stages of training, from preprocessing to generating performance reports.
* Insights and Analysis: Provides detailed summaries, metrics, and visualizations to aid in decision-making.

This repository is a valuable resource for researchers, students, and professionals working on image classification tasks, helping streamline workflows and improve outcomes.

## Clone the repo

install required modules

```bash
  git clone https://github.com/Praveenkottari/Multi-Model-object-Classifier.git
```
```bash
  pip install -r requirements.txt
```    
## Directory structure
    .
    ├── dataset                   #complete dataset
    │   ├── train
    │         ├── class 1
    │         ├── class 2
    │         :
    │   ├── val
    │         ├── class 1
    │         ├── class 2
    │         :
    │   ├── test (optional)       # To test the known labels to check model performnace
    ├── models              
    ├── Results



## Trainning the modle

Clone the project

```bash
  git clone https://link-to-project
```

Go to the project directory

```bash
  cd my-project
```

Install dependencies

```bash
  npm install
```

Start the server

```bash
  npm run start
```


## Running Tests

To run tests, run the following command

```bash
  npm run test
```

## 🔗 Links



