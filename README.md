# Metagenome-Scale Community Metabolic Modelling of Gut Microbiome in Tuberculosis
The repository contains project "Metagenome-Scale Community Metabolic Modelling of Gut Microbiome in Different Forms of Tuberculosis", which explores the taxonomic composition and metabolic activity of gut microbiomes in Tuberculosis. 

## Overview
The project investigates the gut microbiome's composition and metabolic activity in different tuberculosis (TB) forms. The study leverages metagenomic analysis and computational modeling to identify key metabolites influencing TB progression and potential therapeutic targets.

---

## Key Features
- **Metagenomic Analysis**: Taxonomic profiling and diversity analysis of gut microbiome using tools like Kraken2 and QIIME2.
- **Community Metabolic Modelling**: Simulations using the MICOM framework to understand metabolic interactions within microbial communities.
- **Case Study**: Analysis of gut microbiome data from TB-infected individuals in comparison with healthy controls.

---

## Project Structure
- **Data**:
  - Metagenomic datasets retrieved from NCBI SRA.
  - Taxonomic and abundance tables generated from QIIME2 and MICOM.
- **Scripts**:
  - Scripts for data preprocessing, diversity analysis, and metabolic modeling.
- **Results**:
  - Taxonomic profiles, diversity indices, and metabolite flux analyses.
  - Visualizations (Krona pie charts, Pavian Sankey diagrams, etc.).
  - 
---

## Tools and Frameworks
- **Bioinformatics**:
  - Kraken2
  - QIIME2
  - Galaxy Server
- **Community Modelling**:
  - MICOM (Microbiome Metabolic Modelling)
  - AGORA Database
- **Visualization**:
  - Pavian
  - Krona Tools
- **Programming Languages**:
  - Python
  - R (for diversity and statistical analysis)

---

## Methodology
1. **Data Collection**:
   - Retrieval of metagenomic sequences from publicly available datasets.
   - Sample data divided into Active TB, Latent TB, MDR TB, and healthy controls.
2. **Preprocessing**:
   - Quality control using FastQC and trimming with Trimmomatic.
3. **Taxonomic Profiling**:
   - Analysis of gut microbiome composition using Kraken2 and QIIME2.
4. **Metabolic Modelling**:
   - Community model construction with MICOM.
   - Simulation of metabolic fluxes using the Western Diet model.

---

## References
This work references numerous studies and databases including:
- AGORA Database for metabolic models.
- NCBI SRA for gut microbiome sequencing data.

---

