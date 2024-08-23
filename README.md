# Predicting MOF Stability Using RDKit

## Project Overview
This project aims to predict the stability of Metal-Organic Frameworks (MOFs) using molecular descriptors calculated with RDKit and a machine learning model.

## Features
- Data collection and preprocessing
- Molecular descriptor calculation using RDKit
- Stability prediction using a Random Forest model
- Feature importance analysis

## Usage
Clone the repository and run the `MOF_Stability_Prediction.ipynb` notebook. You can input a SMILES string representing a MOF's organic linker and get a predicted stability score.

## Installation
```bash
conda install -c conda-forge rdkit
pip install -r requirements.txt
