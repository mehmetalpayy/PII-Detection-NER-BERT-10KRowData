<h1 align="center"><strong>PII Detection with NER-BERT</strong></h1>

## Overview

This repository contains a project focused on detecting Personally Identifiable Information (PII) using Named Entity Recognition (NER) with the BERT model. The project includes comprehensive Jupyter Notebooks that detail the process of fine-tuning BERT for PII detection, data preparation, and practical implementation examples.

## Repository Structure

- **`10kdata.csv`**: This file contains a dataset with over 10,000 rows of annotated data, specifically used for training and fine-tuning the BERT model for PII detection.
- **`BERT Fine-Tuning.ipynb`**: A Jupyter Notebook that provides a step-by-step guide on fine-tuning the BERT model using the `10kdata.csv` dataset. This notebook covers data loading, preprocessing, model configuration, and training.
- **`HuggingFace Example.ipynb`**: A Jupyter Notebook showcasing the fine-tuning process of the BERT model using Hugging Face's `load_dataset` method. It provides a detailed walkthrough of the BERT fine-tuning process, including command-line instructions and configuration details.

## Project Details

### Data and Model Fine-Tuning

The `10kdata.csv` dataset is used in the `BERT Fine-Tuning.ipynb` notebook to train a BERT model specifically for the task of detecting PII. The notebook includes:

- Data loading and preprocessing steps.
- Model configuration, including hyperparameters and training settings.
- Fine-tuning procedure with BERT.
- Evaluation of model performance on a validation set.

The `HuggingFace Example.ipynb` notebook demonstrates how to use Hugging Face's `datasets` library to load data and fine-tune BERT, providing an alternative approach to model training.

### Useful Links

- [Medium Article on NER](https://medium.com/@balci.pelin/ner-8eb9694ccad3): An article detailing NER concepts and applications.
- [YouTube Tutorial: NER with BERT](https://www.youtube.com/watch?v=uKPBkendlxw&t=1089s): A video tutorial on using BERT for NER.
- [YouTube Tutorial: Fine-Tuning BERT](https://www.youtube.com/watch?v=dzyDHMycx_c&t=1s): A video guide on fine-tuning BERT models.

## Getting Started

To get started with this project, follow these steps:

1. **Clone the Repository**
   ```bash
   git clone https://github.com/mehmetalpayy/PII-Detection-NER-BERT-10KRowData.git
   cd PII-Detection-NER-BERT-10KRowData

2. **Explore the Notebooks**

    - Open `BERT Fine-Tuning.ipynb` to understand how to fine-tune the BERT model using the provided dataset.
    - Open `HuggingFace Example.ipynb` to see how to use Hugging Face tools for model training.

3. **Review the Results**

    - The BERT Fine-Tuning.ipynb notebook will show the training process and results of the BERT model fine-tuning.
    - The HuggingFace Example.ipynb notebook provides insights into using Hugging Face's tools for model training and evaluation.

## Contributing

Contributions to the project are welcome. If you have suggestions, improvements, or bug fixes, please fork the repository and submit a pull request.

## Contact

For any questions or feedback, please reach out to me at [mehmetcompeng@gmail.com](mailto:mehmetcompeng@gmail.com).

---
