# Aspiring Bioinformatics Analyst

## About Me
 I am a passionate about Bioinformatics with a strong background in molecular biology, and my enthusiasm for this field is rooted in my ability to unravel complex biological data.  I thrive on the challenge of preprocessing and normalizing data to uncover meaningful insights through analysis, and my comfort with the command line allows me to efficiently navigate and manipulate datasets.  My dedication lies in bridging biology and computational science to contribute to our understanding of diseases and advance biomedical research.

#### Skills: Python, UNIX, ScanPY, MATLAB, STAR, SRATOOLS, BLAST, NextFlow, pyDEseq2, gseaplot

## Education
B.S., Molecular, Cellular, and Developmental Biology | The University of Washington (_June 2023_)

## Projects
### [Project 1: Breast Cancer T-Cells Single Cell RNA Analysis: Project Overview](https://github.com/JoshTjan/Breast_Cancer_Tcells_SCRNA_Analysis_Project)
* This project focuses on the analysis of publicly available single-cell RNA sequencing (scRNA-seq) data related to breast cancer T cells. 
* The scRNA-seq data used in this project was obtained from publicly available sources. Please refer to the data source or repository for detailed information on the dataset.
* Data Preprocessing: Prior to analysis, the raw scRNA-seq data underwent a series of preprocessing steps. This included quality control, filtering out low-quality cells, and removing unwanted sources of variation.
* Normalization: To ensure that the data was comparable across all cells, normalization was performed. This step is crucial for accurate downstream analysis.
* Clustering: Clustering analysis was carried out to group cells with similar gene expression profiles. This allowed for the identification of distinct cell populations, including T cells, within the breast cancer dataset.
* Gene Identification: Genes associated with T cells were identified through differential gene expression analysis. This step aimed to highlight genes that are specifically expressed in T cells or show significant differences in expression compared to other cell types.
  
![BC_Cluster](/image/BC_Cluster_Labeled.png)![](/image/CD8+marker_dot.png)
![](/image/Memory_Tcell.png)
![](/image/cd4_dot.png)


### [Project 2: RNA-seq Analysis of Superior Cervical Ganglia (SCG) from Healthy and Heart Disease Samples: Project Overview](https://github.com/JoshTjan/RNA-seq-Analysis-of-Superior-Cervical-Ganglia-SCG-from-Healthy-and-Heart-Disease-Sample)
* This project performs bulk RNA-seq analysis on SCG samples obtained from healthy and heart disease donors.
* Data Retrieval: The first step is to retrieve the RNA-seq data from the SRA (Sequence Read Archive) using SRAtools. The following geo data set was used GSE231763.
* Genome Index Generation:B efore aligning the reads, built a genome index using STAR with FASTA and gene annotation GTF file.
* Alignment: With the genome index in place, we alligned the RNA-seq reads to the reference genome using STAR.
* Count Table Generation: Next, we generate a count table from the aligned BAM files using featureCounts.
*  Differential Expression Analysis: We perform differential expression analysis using pyDESeq2. The code for this step can be found in the Jupyter notebook.
*  Visualization: To visualize the results, we used gseaplot for generating plots. The plots for creating heatmaps and volcano plots can be seen below.
*  Gene Ontology Enrichment Analysis: In this project, we conducted Gene Ontology (GO) enrichment analysis to gain insights into the biological processes, molecular functions, and cellular components associated with the differentially expressed genes (DEGs) identified in our RNA-seq data shown below.
*  Results: This analysis identified key genes and interesting findings related to the disruption of the physiologic sleep-wake cycle and low melatonin levels in cardiac disease.

![](/image/DE_genes_heatmap.png)
![](/image/volcano.png)
![](/image/DE_genes_plot.png)
![](/image/enrichment.png)


### [Project 3: Diabetes Prediction: Project Overview](https://github.com/JoshTjan/Diabetes_Prediction)
* In this project, I aimed to predict the onset of diabetes based on diagnostic measures using a dataset containing various medical predictor variables and one target variable, Outcome. The predictor variables encompassed factors such as the number of pregnancies, BMI, insulin levels, age, and more.
* Data Exploration: I started by exploring the data using Python. I analyzed the distributions of the features and the relationships between them. This step helped me understand the data better and informed the subsequent steps.
* Data Preprocessing: I preprocessed the data by handling missing values and scaling the features. This step is crucial as it can significantly impact the performance of the machine learning models.
* Model Training and Evaluation: I trained and evaluated several machine learning models, including Logistic Regression, Random Forest, and Support Vector Machine. I calculated several metrics, such as accuracy, precision, recall, and F1 score, to evaluate the performance of the models.
* Hyperparameter Tuning: I improved the performance of the Random Forest model by tuning its hyperparameters using grid search. Hyperparameter tuning is an important step as it can help us find the most optimal parameters for our model, thus improving its performance.

![](/image/Dia_Pred.png)
