---
title: "Histographs: Graphs in Histopathology"
collection: publications
permalink: /publication/histograph_spie_2019
date: 2019-10-15
excerpt: In this work, we propose to classify cancers using graph convolutional networks (GCNs) by modeling a tissue section as a multi-attributed spatial graph of its constituent cells.
venue: 'SPIE Medical Imaging 2020'
image: 'graph_path_flow.png'
width: '800'
---
Spatial arrangement of cells of various types, such as tumor infiltrating lymphocytes and the advancing edge of a tumor, are important features for detecting and characterizing cancers. However, convolutional neural networks (CNNs) do not explicitly extract intricate features of the spatial arrangements of the cells from histopathology images. In this work, we propose to classify cancers using graph convolutional networks (GCNs) by modeling a tissue section as a multi-attributed spatial graph of its constituent cells. Cells are detected using their nuclei in H&E stained tissue image, and each cell's appearance is captured as a multi-attributed high-dimensional vertex feature. The spatial relations between neighboring cells are captured as edge features based on their distances in a graph. We demonstrate the utility of this approach by obtaining classification accuracy that is competitive with CNNs, specifically, Inception-v3, on two tasks-cancerous versus non-cancerous and in situ versus invasive-on the BACH breast cancer dataset.
### Citation 

'<b>Anand, D.</b>,Gadiya, S., and Sethi, A. (2019). &quot;Histographs: Graphs in Histopathology.&quot; <i>SPIE Medical Imaging 2020.</i><b>(Equal contribution by Anand D. and Gadiya S.)</b>.'

[Paper Link](https://arxiv.org/abs/1908.05020)
