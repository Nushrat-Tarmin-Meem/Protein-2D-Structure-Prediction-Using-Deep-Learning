# <i>Protein-2D-Structure-Prediction-Using-Deep-Learning</i>

## NCBI Dataset Used: 
RefSeq Non-redundant Protein Database (RefSeq WP Acessions) Bacterial Protein Families (Enterobacteriaceae, Escherichia etc.)

## Importing Required Libraries:
<li>import os</li>
<li>import tensorflow as tf</li>
<li>import numpy as np</li>
<li>import matplotlib.pyplot as plt</li>
<li>import seaborn as sns</li>
<li>import imageio.v2 as imageio</li>

## Data Preprocessing:

<table>
  <tr><th>Loading Fasta Sequences</th></tr>
  <tr><td>fasta_file = "/kaggle/input/ncbi-data/ncbi_dataset/ncbi_dataset/data/GCF_963681135.1/protein.faa"</td></tr>
  <tr><th>Loading Sequences and Labels</th></tr>
  <tr><td><img align="left" alt="" height="120" src="https://github.com/user-attachments/assets/b1fbaa1f-b476-4f0d-af04-aa8e2f1de37f"></td></tr>
  <tr><th>Tokenizing Sequences</th></tr>
  <tr><td><img align="left" alt="" height="160" src="https://github.com/user-attachments/assets/6a42c436-5ad9-4a1d-af6f-7fb80c905d5c"></td></tr>
  <tr><th>Padding Sequences and Encoding Labels</th></tr>
  <tr><td><img align="left" alt="" height="250" src="https://github.com/user-attachments/assets/dd233d49-e4c1-484a-9799-12a3b110dafa"></td></tr>
  <tr><th>Bar Chart of Class Distribution (One-Hot Encoded Labels)</th></tr>
  <tr><td><img align="left" alt="" height="400" src="https://github.com/user-attachments/assets/616f5353-897b-4706-9cc5-7e494f39622d"></td></tr>
</table>

## Train-Test Splitting:
![image](https://github.com/user-attachments/assets/f8235065-67eb-444f-953e-1e3cc080f44b)

## Model Structure:
![image](https://github.com/user-attachments/assets/a763c1b0-07d9-41dd-adb8-4eb505eb6a2e)

## GIF Showing the Weight Updates at Each Epoch and Layer:

## Loss Curve:

## Accuracy Curve:

## Confusion Matrix:

## Evaluation Metrics:
