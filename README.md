# federated-learning
This repository contains all the ressources published within the scope of this master thesis.

## Thesis objectives

Within the scope of this thesis, the author explores new possibilities to leverage machine learning on decentralized health data by developing a **prototype solution with the FL framework from TensorFlow**. Following the design science research methodology proposed by the authors of Peffers et al. (2007), the objective of the design and development phase is to work with a concrete health care use case to make the prototype solution more tangible. 

There are many different health care use cases and types of decentralized health data that could have been chosen for the prototype development phase of this thesis. To limit the scope, the author chose to work with the example of a skin lesion type classification, using the **open-source HAM10000 dataset**. Thus, it is important to note that this thesis only practically explores one type of machine learning model and one type of health data. Concludingly, a generalization of whether federated learning can be implemented for applications in the health care and medical industry, can only be formulated in a limited way beyond the explored use case. 

## Research questions

## Overview of the most important Python notebooks

Most important ressources are the following:

*   Tutorial Federated Learning for Image Classification [tff_tutorial_federated_learning_for_image_classification.ipynb](https://github.com/ChristinaSalker/federated-learning/blob/master/tutorial_federated_learning_for_image_classification.ipynb)

*   Centralized ML process using the HAM10000 dataset [tff_skin_lesion_classification_etl_v6.ipynb](https://github.com/ChristinaSalker/federated-learning/blob/master/tff_skin_lesion_classification_etl_v6.ipynb)

*   The final prototype for FL using the HAM10000 dataset [tff_skin_lesion_classification_final_prototype_v3.ipynb](https://github.com/ChristinaSalker/federated-learning/blob/master/tff_skin_lesion_classification_final_prototype_v3.ipynb)

## Requirements to run the noetbooks

*   Google Account (to use Google Drive and Google Colab)
*   Kaggle Account (to create a Kaggle token for Colab)

Setting up these accounts is for free. This article [Setting Up Kaggle in Google Colab](https://towardsdatascience.com/setting-up-kaggle-in-google-colab-ebb281b61463) by Anne Bonner is a great help to configure the Kaggle and Colab environment.
