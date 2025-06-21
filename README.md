# 🧬 GraphSAGE-based Multi-omics Biomarker Identification in Bladder Cancer

This repository contains the code, models, and results for the study:

> **GraphSAGE-based Approach for Age-specific Multi-omics Biomarker Identification in Bladder Cancer**  
> Usman Fakhar, Mohammad Elshafie, Abedalrhman Alkhateeb  
> Department of Computer Science, Lakehead University, Thunder Bay, Ontario, Canada  
> Contact: ufakhar@lakeheadu.ca

## 📄 Abstract

Bladder cancer presents significant age-related heterogeneity in its molecular landscape and outcomes. This project leverages Graph Neural Networks (GNNs)—specifically **GraphSAGE**—to identify **age-specific biomarkers** by integrating **multi-omics data** including:

- mRNA Expression  
- DNA Methylation  
- Copy Number Alterations (CNA)

Patient **age** is embedded as both a **graph feature and a stratification factor**, enabling the model to capture nuanced age-dependent molecular signatures. The model achieved:

- **Accuracy**: 82.84%  
- **AUC**: 0.8804
