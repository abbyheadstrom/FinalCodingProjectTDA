# An Exploration of Topological Data Analysis (TDA) and Persistent Homology for Arrhythmia Detection 

#### Authors: Abby Headstrom & Abby Irish

Our project explores the method of persistent homology used in topological data analysis (TDA), which characterizes the shape of data using holes. Holes are a significant topological feature in many data sets and tend to be robust to noise. This can be represented by persistence diagrams, which are collection of points, each corresponding to a feature that appears at scale x and disappears at scale y. Persistence diagrams can then be used to create persistence images which are a type vector representation needed in order to perform ML techniques such as SVM. We used the ECG5000 dataset which is a collection of ECG signals of arrhythmatic heartbeats that can be classified into four different types of abnormalities.

Datasets: https://github.com/abbyirish3/FinalCodingProjectTDA/tree/main/ECG5000

Relevant research papers: 
- "Topological Data Analysis for Arrhythmia Detection through Modular Neural Networks" https://arxiv.org/pdf/1906.05795
- "Persistence Images: A Stable Vector Representation of Persistent Homology" https://jmlr.csail.mit.edu/papers/volume18/16-337/16-337.pdf
- "Multiparameter Persistence Images for Topological Machine Learning" https://web.ma.utexas.edu/users/blumberg/camera-ready.pdf
