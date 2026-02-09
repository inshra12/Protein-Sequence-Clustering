# Protein-Sequence-Clustering

This is my ** bioinformatics project** where I explored clustering protein sequences using embeddings from **ProtBERT** and **ESM2**.

---

## Dataset

* 305 protein sequences in FASTA format
* Families: Hemoglobin, Lysozyme, Kinase, Unknown

---

## What I did

1. Converted protein sequences into embeddings (ProtBERT / ESM2)
2. Visualized embeddings with PCA and t-SNE
3. Clustered sequences using K-Means
4. Compared clusters with true families (for evaluation only)

---

## Results

* **ProtBERT:** ~41% clustering accuracy, clusters overlap
* **ESM2:** ~80% clustering accuracy, much better separation

---

## Learnings

* How protein embeddings work
* Difference between PCA and t-SNE
* Basic unsupervised clustering and evaluation

---

## Files

* `Protein_Sequence_Clustering_ProtBert.ipynb` – ProtBERT embeddings
* `Protein Sequence Clustering using ESM2 Embeddings.ipynb` – ESM2 embeddings
* `proteinSequences.fasta` – input sequences
