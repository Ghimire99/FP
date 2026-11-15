# Proposal
## Project Description
For my final project, I plan to perform RNA-seq differential gene expression analysis in poultry. The goal is to identify genes that are significantly upregulated or downregulated in treated birds compared to untreated control birds.

My original plan was to use RNA-seq data from an ongoing study in our laboratory. In this study, birds are assigned to different treatment groups and a control group. However, because the experiment is still ongoing and sequencing data will likely not be available before the project deadline, I plan to use a publicly available poultry RNA-seq dataset instead.

I am currently considering using GEO dataset GSE135272. This dataset contains RNA-seq data from ileum tissue of broiler chickens that were fed either a control diet or a diet supplemented with the antibiotic growth promoter avilamycin. The dataset includes biological replicates in both treatment and control groups, making it suitable for differential gene expression analysis.

The project will produce quality-control reports, gene expression count tables, lists of differentially expressed genes and visualizations such as PCA plots, heatmaps and volcano plots.

## Technical Workflow
I currently plan to use the following workflow:

1. Download the RNA-seq data and sample information.
2. Organize the data and create the project directory structure.
3. Check read quality using FastQC.
4. Summarize FastQC results using MultiQC.
5. Trim adapters and low-quality bases using TrimGalore.
6. Align reads to the chicken reference genome.
7. Generate gene count data.
8. Import the count data into R.
9. Perform differential gene expression analysis using DESeq2.
10. Identify genes that are upregulated or downregulated in the treatment group compared with the control group.
11. Create PCA plots, heatmaps and volcano plots to visualize the results.
12. Summarize the analysis and results in a Quarto report.

## Uncertainities and Challenges 
The biggest uncertainty is the dataset that will be used. My preferred project is based on an ongoing experiment in our laboratory, but the sequencing data will likely not be available before the final project deadline. Therefore, I will likely use a publicly available poultry RNA-seq dataset.

I am also still learning some aspects of RNA-seq data analysis, including generating gene counts, performing differential gene expression analysis and interpreting the biological meaning of differentially expressed genes. Some parts of the project will involve topics that will be covered later in the course, including DESeq2 and Quarto. Thus, depending on the dataset and available time, some parts of the workflow may need to be adjusted.

## Why I choose this project
I chose this project because it is similar to a study that is currently being conducted in my laboratory. The ongoing study is investigating the effects of a compound treatments in birds and I am interested in learning how RNA-seq data can be used to identify genes that respond to the treatment.

Since the sequencing data from our study will likely not be available before the project deadline, I plan to analyze a publicly available poultry RNA-seq dataset with a similar treatment-versus-control design. This will allow me to learn the same analysis methods that I hope to apply to our own data in the future.

This project will help me gain practical experience with RNA-seq analysis, differential gene expression analysis, data visualization and reproducible bioinformatics workflows. The skills I learn from this project will be useful for my future research and dissertation work.

## References
RNA-Seq analysis of broiler intestinal transcriptome reveals new insight on the interaction between antibiotic growth promoters (AGPs) and the host.
https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE135272

