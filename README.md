# Semantic Segmentation of Clothing items using Fashionpedia dataset
---
The goal of this project is to investigate several state-of-the-art segmentation algorithms presented in high impact journals, select one, and implement it in a fashion parsing task. To do so, the network will be employed to perform semantic segmentation of images present in Fashionpedia, a dataset where 46 distinct clothing items are segmented in a total of 48,825 images. The dataset can be visualized and download at: https://fashionpedia.github.io/home/Fashionpedia_download.html.

The project contains the following notebooks:
* `Exploratory_Data_Analysis.ipynb:` Results for the exploratory data analysis of the Fashionpedia dataset.
* `PointrendLarge.ipynb:` Notebook to run the R101-FPN PointRend model.
* `PointrendSmall.ipynb:` Notebook to run the R50-FPN PointRend model.
* `Results_Analysis.ipynb:` Notebook providing all the quantitative and qualitative results of the project.
* `Segment_Anything_Fashionpedia.ipynb:` Notebook exploring the Segment Anything Model (SAM).