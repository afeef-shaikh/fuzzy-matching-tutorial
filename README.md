# Fuzzy Matching with Dedupe – A Beginner-Friendly Tutorial

This repo contains a hands-on Google Colab tutorial that walks through how to clean and cluster **messy organization names** using the [`dedupe`](https://github.com/dedupeio/dedupe) Python library.

You'll learn:
- Why exact matching fails in messy datasets
- How to clean and preprocess text fields like company or organization names
- How to use `dedupe` to group similar names together using fuzzy matching
- How to assign canonical (cleaned) names for analysis

---

## Tutorial Notebook

▶ **[Click here to open in Colab](https://colab.research.google.com/github/afeef-shaikh/fuzzy-matching-tutorial/blob/main/Tutorial_Cleaning_Messy_Names_with_Dedupe.ipynb)**  


---

## What This Tutorial Covers

✅ Generate a small fake dataset of messy names  
✅ Clean names using basic text rules (lowercasing, removing punctuation, etc.)  
✅ Train a `dedupe` model with just a few labeled examples  
✅ Group (cluster) similar names  
✅ Assign canonical names back to the dataset  
✅ Export cleaned results for further use

---

## Example Output 
Cluster 1: amazon
amaz0n
ama zon
amazon inc

Cluster 2: facebook
facebook llc
face book
fac ebook


---

## Why This Matters

Real-world datasets (job postings, donors, org lists, etc.) often contain inconsistently written names.  
This tutorial helps you standardize them with minimal manual effort — making your analysis more reliable.

---

## Requirements

- Python ≥ 3.7  
- [`dedupe`](https://docs.dedupe.io/en/latest/Installation.html)  
- `pandas`, `re` (standard lib)

Colab takes care of setup automatically — just open and run!


## ✨ Made with ❤️ by Afeef Shaikh

