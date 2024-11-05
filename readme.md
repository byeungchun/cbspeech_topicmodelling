# Topic Modeling Notebook

## Overview
This notebook is designed to build a topic model using natural language processing techniques. The model processes textual data, identifies themes within the content, and outputs the topics that characterize the data set. It utilizes machine learning and NLP libraries such as **scikit-learn** and **gensim** for processing and model building.

## Required JSON File
The notebook requires a JSON file named `centralbank_speech_201910.json`, which should be located in the same folder as the notebook. This file contains the data for topic modeling and should be structured as follows:
- Each entry in the JSON file should represent a document or text item.
- Text data should be in a specified key (e.g., "text") as processed in the notebook.

Ensure your JSON file is formatted correctly and loaded as specified in the notebook’s code cells.

## How to Execute the Notebook on Google Colab Using GPU
To run this notebook on Google Colab with GPU support:
1. Open the notebook and click on the provided **Google Colab link**.
2. In Colab, navigate to **Runtime > Change runtime type**.
3. Set **Hardware accelerator** to **GPU** and save.
4. Ensure the necessary libraries (e.g., `scikit-learn`, `gensim`) are installed within the Colab environment.
5. Execute each cell sequentially, following any instructions provided for data loading and preprocessing.

This setup provides enhanced processing power, enabling faster model training and analysis.
