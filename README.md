# Alzheimer's-disease-regulatory-region-analysis
Contains computer code and data to investigate Alzheimer's disease genome-wide association regions for regulatory function.
+
+
These files contain the computer code and data used to generate the Tables and Results for the paper “Bioinformatics pipeline to guide late-onset Alzheimer’s disease (LOAD) post-GWAS studies: Prioritizing transcription regulatory variants within LOAD associated regions. “

The bioinformatics pipeline and all associated steps are shown in Figure 1 in the manuscript and in the Methods section.  The example file shows screen shots of the UCSC Table browser to download the specific datasets used in the analysis.  The script file shows the R script used to run MotifbreakR to identify transcription factor binding sites that are disrupted by the SNPs identified earlier in the pipeline.  Intermediate steps, to construct the analysis datasets are done using the software package JMP (SAS Institute, Cary NC) to perform the table joins and subsetting operations needed to implement the bioinformatics pipeline.

All data loaded from the UCSC Genome browser (GRCh37/hg19) was current as of 5/8/2020.

Files:
Examples of UCSC Table Browser and GTEx settings to implement pipeline.docx – This file contains examples of the parameter settings for the UCSC Table browser and the GTEx portal to download the necessary data to implement the pipeline.  All of the steps illustrated in Figure 1 of the manuscript are covered in the examples.

Example MotifbreakR script.docx – R script that illustrates how the MotifbreakR package is used to assess SNP effects on transcription factor binding sites as described in the manuscript.

Supplemental Tables TRCI.xlsx – EXCEL workbook containing all of the supplementary tables in the manuscript.  These tables are the data that was used in the analysis reported in the paper.

Table 1.xlsx – Table 1 from the manuscript in EXCEL format 
