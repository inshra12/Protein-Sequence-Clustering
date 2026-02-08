# Protein-Sequence-Clustering
Protein Sequence Clustering with ProtBert
Overview

This is a practice project on protein sequence analysis. It uses ProtBert embeddings to represent protein sequences, then applies PCA, t-SNE, and K-means clustering to visualize and group similar proteins.

Features

Read protein sequences from a FASTA file

Convert sequences into ProtBert embeddings

Reduce dimensions with PCA and t-SNE

Cluster proteins using K-means

Visualize clusters and compare with true protein families

Requirements
pip install biopython transformers torch scikit-learn pandas numpy matplotlib seaborn

How to Run

Place your protein sequences in proteinSequences.fasta

Open the notebook Protein_Sequence_Clustering_ProtBert.ipynb

Run all cells to see embeddings, clustering, and plots

Results

Some protein families (e.g., Lysozyme) cluster well

Others (e.g., Kinase) are mixed

Accuracy without ‘Other’ family: ~48%

Notes

This is a practice project to learn protein embeddings, visualization, and unsupervised clustering.
