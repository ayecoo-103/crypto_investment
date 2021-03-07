Background
As a role of a fiancial advisor, my task is to create a prototype to submit crypto portfolio using a machine learning. First, I will cluster Cryptocurrencies with K-means and will find the best 'k' value by coding the elbow method algorithm and will utilize hvplot scatter to visulizing clusters. 

Required libraries and dependencies:
import pandas as pd
import hvplot.pandas
from path import Path
from sklearn.cluster import KMeans
from sklearn.decomposition import PCA
from sklearn.preprocessing import StandardScaler
