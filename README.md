# LLMiniST: Advanced Spatial Niche Identification Using Large Language Models

LLMiniST is an innovative framework that leverages large language models (LLMs) to identify spatial niches in spatial transcriptomic datasets. By integrating gene expression, spatial context, and biological knowledge, LLMiniST sets a new standard for tissue niche identification and analysis.

## Features

- **Zero-Shot Spatial Contextual Analysis**: Use pre-trained LLMs to predict tissue niches without requiring dataset-specific training.
- **Fine-Tuning Capabilities**: Implement a two-stage fine-tuning strategy for adapting LLMs to new spatial datasets, enhancing cross-subject generalizability.
- **Spatial Context Prompt Engineering**: Transform spatial transcriptomic data into structured prompts, incorporating gene expression profiles, spatial locations, cell types, and external biological knowledge.
- **Robust Benchmarking**: Compare LLM-based clustering with state-of-the-art non-LLM methods across datasets such as STARmap, MERFISH, and Visium.

## Applications

- **Tissue Atlas Construction**: Delineate spatial niches to map tissue structures.
- **Disease Insights**: Identify niche-specific markers and spatial signatures of diseases.
- **Molecular Network Discovery**: Infer regulatory networks within identified niches.

## Why LLMiniST?

LLMiniST showcases the potential of large language models in spatial transcriptomics, outperforming traditional methods in accuracy, interpretability, and generalizability. By integrating prior biological knowledge with spatial data, LLMiniST advances the field of bioinformatics and spatial biology.

## Documents Description
`subject_qc_plots.pdf`: Quality Control plots for 48 BI lung samples. 
`non_integration_analysis.pdf`: UMAP analysis without the integration. 
`integration_analysis.pdf`: UMAP analysis with the integration.
`scatter_plots.pdf`: Scatter plots for nFeature_RNA v.s. nCount_RNA and percentage of mt v.s. nCount_RNA.
`violin_plots.pdf`: Violin plots for nFeature, nCount, and percentage of mt grouped by 12 subjects.
`violin_plots_by_subjects.pdf`: Violin plots for nFeature, nCount, and percentage of mt grouped by 48 samples, colored by 12 subjects.
`violin_plots_by_subjects_with_regions.pdf`: Violin plots for nFeature, nCount, and percentage of mt grouped by 48 samples, colored by 12 subjects, labeled on x-axis as `subject_name + 4 areas (R1, R2, R3, and R4)`. 
---
