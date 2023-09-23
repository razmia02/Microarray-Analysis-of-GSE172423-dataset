# Microarray-Analysis-of-GSE172423-dataset
Microarray analysis of NCBI dataset for differential gene expression during genital herpes. This is a time-series dataset consisting of samples from patients undergoing lesion stage, 2-weeks post-infection and 8-weeks post-infection. 
The dataset was already normalized, but the intensity values of some genes were found to be in the negative range. To obtain all positive values for the genes, the data was log2 transformed and an offset was added. 
After transformation, heatmaps and PCA plots were constructed to identify the trends and correlations within the dataset. 
For DEG analysis, limma package of RStudio was utilised. 3 different contrasts were made between groups. 
The contrast matrices were as follows:
1- Contrast-1 between lesion and 2-weeks post-infection group
2- Contrast-2 between 2-weeks and 8-weeks post-infection group
3- Contrast-3 between lesion and 8-weeks post-infecyion group. 
After the DEGs were analysed between three contrast, common genes were identified by constructing venn diagram. 97 genes were found common between three states of the disease. 
