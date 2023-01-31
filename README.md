# LATAM-FAKE-NEWS-TRANSFORMER-MODELS
This repository contains the code and data for a data science project that aims to predict instances of fake news in Latin America using state-of-the-art transformer models. The project uses a combination of natural language processing techniques and machine learning to classify social media posts as real or fake. The goal of the project is to help combat the spread of disinformation and promote an informed populace. The repository includes the code for data preprocessing, model training, and evaluation, as well as the dataset used for the project. It is implemented in python, using popular libraries such as pandas, numpy, and transformers from Hugging Face. Due to limited space on Github some results are saved on [Google Drive](https://drive.google.com/drive/folders/1oAzFYXfBd9lO-9DcNCHgUgX2SrBGIO62?usp=sharing)


# 📁 Data
This folder contains a collection of data that is used for training and making predictions with machine learning models. The original dataset is used for training the models and is a labeled dataset with the inputs and their corresponding outputs. The inference datasets, on the other hand, are unlabeled datasets for which the models will make predictions. The folder also contains the results of the predictions made on the inference datasets, saved in [Google Drive](https://drive.google.com/drive/folders/1H48R_mi-P2DFGsi1_U2vqwNl0-ytpnWu?usp=sharing).


#  📁 Notebooks
The folder of Notebooks contains all the notebooks used in the project, organized by stage. This structure makes it easy to manage the project and keep track of the progress made at each stage.

The first stage is **Exploratory Data Analysis (EDA)**, where the initial data is explored and analyzed to understand its properties, patterns, and relationships. The notebook in this stage includes data cleaning and preprocessing.

The second stage is **Topic Modeling**, where the main topics discussed in a collection of text data are identified and extracted. The notebooks contains natural language processing techniques such as tokenization, stop word removal, and lemmatizers, as well as machine learning algorithms such as Latent Dirichlet Allocation (LDA) or Non-Negative Matrix Factorization (NMF) to identify the underlying topics in the text data.

The third stage is **Transformer Models**, where the performance of different transformer models is fine-tuned and compared. The notebook in this stage use pre-trained transformer models such as BERT and ELECTRA.

The final stage is **Inference**, where the models are used to make predictions on an unlabeled dataset. The notebook in this stage will use the best model from the previous stage and make predictions on the unlabeled data.


#  📁 Models

The folder of Models stores the weights and configurations of every algorithm that was tried as part of the project. This folder serves as a record of all the models that were trained, tested, and evaluated, and provides a historical record of the models and their results. The models in this folder are saved in a format that can be easily loaded and used for making predictions, allowing for quick and efficient inference. Each model stored in this folder is a snapshot of its configuration and weights at a particular point in time, capturing its state after being trained on the original dataset. PyTorch models saved in [Google Drive](https://drive.google.com/drive/folders/1dztKG6IY1PYUWpDLh741HUNsaQ3nIdh5?usp=sharing).
