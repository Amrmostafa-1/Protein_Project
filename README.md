# Protein Renaissance: The Age of Sequence Generation

## Overview
A deep learning approach designed to generate novel protein sequences. Leveraging state-of-the-art neural architectures, our project aims to facilitate the discovery of new proteins, potentially leading to advancements in fields like drug discovery, bio-engineering, and more.

## Technologies Used

- Deep Learning Framework: TensorFlow & Keras
- Language Processing Library: Transformers by HuggingFace
- Pre-trained Protein Model: ProteinBert from RostLab
- Data Manipulation: pandas
- Visualization: Seaborn

## Features

- Species Classification: Deduce if the surfaced protein sequence has its roots in humans or rats.
- Sequence Generation: Capitalize on trained models to unearth new protein sequences.
- ProteinBert Integration: Distill intricate protein features utilizing the distinguished ProteinBert model.
- Validation against PDB: Validate the singularity of generated sequences against nature's repertoire using the PDB API.(https://www.rcsb.org)

## Dataset

- The backbone of this project is constructed on a dataset amassing protein sequences, demarcated by species origin (Human or Rat), which was downloaded from UniProt.
https://www.uniprot.org


## References
- Alphafold 2 notebook was used to predict the folding of the generated sequence.
https://colab.research.google.com/github/sokrypton/ColabFold/blob/main/AlphaFold2.ipynb?authuser=1#scrollTo=KK7X9T44pWb7
- https://www.tensorflow.org/api_docs/python/tf
