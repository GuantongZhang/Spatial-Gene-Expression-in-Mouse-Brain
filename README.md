# Exploring Spatial Gene Expression Patterns in the Mouse Brain

The evaluation of gene expression and its relation to spatial data is a topic that is highly relevant in Neurobiology. We want to determine which pairs of genes and cell coordinates have high levels of co-expression. Finding these patterns of co-expression will give us insights about how spatial location of cells is related to gene expression and can affect the function of genes.

To accomplish this, we implement clustering and regression techniques to find relationships and patterns within a dataset of mouse brains. The dataset contains the different genes and cell coordinates present within a single mouse brain. We analyzed 3 relationships within our data: gene expression with other cell samples, gene expression with other genes, and gene expression with other spatial coordinates of the cells. We used a correlation matrix to find which gene pairs are highly-coexpressed and compared with the expression patterns of gene location pairs that were found through k-means clustering.

From these correlation matrix heatmaps, we found that there exists both patterns of high co-expression and spatial correlation between genes epha3 and gfap, as there exists a high level of co-expression between both genes, as well as the genes sharing similar coordinates. A similar pattern can be shown in sox2 and lef1. This gives us some insight about how these two genes can both be related in terms of neural development.

# Authors

- Aditi Sadwelkar
- Aparajita Pranjal
- Benjamin Xue
- Guantong Zhang
- Uyen Tran