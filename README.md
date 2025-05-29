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
  <tr><td><img align="left" alt="" height="420" src="https://github.com/user-attachments/assets/616f5353-897b-4706-9cc5-7e494f39622d"></td></tr>
</table>

## Train-Test Splitting:
![image](https://github.com/user-attachments/assets/f8235065-67eb-444f-953e-1e3cc080f44b)

## Model Structure:
![image](https://github.com/user-attachments/assets/fec0f1c1-687e-45f8-8dba-5192c37419b1)

## GIF Showing the Weight Updates at Each Epoch and Layer:
![layer1_weights](https://github.com/user-attachments/assets/9a2b1c1e-b651-453b-8785-60784ba82a40)
![layer2_weights](https://github.com/user-attachments/assets/47dd9364-99f6-4816-8cd4-78e0707da961)
![layer3_weights](https://github.com/user-attachments/assets/7f9765ec-1269-4870-b08c-1c72872b2148)
![layer5_weights](https://github.com/user-attachments/assets/9d014940-5ac7-4177-a648-87148e725678)
![layer6_weights](https://github.com/user-attachments/assets/9f99776f-99d1-4c1e-9449-88e1f09814c9)
![layer8_weights](https://github.com/user-attachments/assets/e75a42f5-c9e8-4c5c-bed4-14f7d2ccaa64)

## Loss and Accuracy Curve:
![image](https://github.com/user-attachments/assets/4adf3b66-f18b-4c48-b2b2-c1c85af9e0a6)

## Confusion Matrix:
![image](https://github.com/user-attachments/assets/72a2d558-9c92-4e5e-ab22-55434358cd3e)

## Evaluation Metrics:
![image](https://github.com/user-attachments/assets/c2b044d8-616c-45ab-b8ac-b193ffbf7ff3)
