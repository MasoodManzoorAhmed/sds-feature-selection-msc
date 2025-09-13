## SDS-feature-selection-MSc
# "MSc Data Science dissertation: Stochastic Diffusion Search for Optimized Feature Selection Across Diverse Datasets"
# Project Overview
This repository demonstrates advanced feature selection techniques for high-dimensional datasets using Stochastic Diffusion Search (SDS)—an agent-based swarm intelligence algorithm—alongside established methods such as Recursive Feature Elimination (RFE), Principal Component Analysis (PCA), and Mutual Information (MI). The project benchmarks the effectiveness of SDS against traditional approaches in terms of accuracy, feature reduction, and scalability across nine distinct real-world datasets.
All data preparation, modeling, and analysis tasks were conducted in Google Colab for seamless, reproducible execution. Datasets are securely stored in Google Drive, ensuring easy access and collaborative workflow.

# How to Use
Open the Google Colab notebooks from this repository or your own Drive.
Connect to your Google Drive using drive.mount('/content/drive') at the start of each notebook for access to the datasets.
Run the code blocks in sequence for data exploration, preprocessing, feature selection, model training, comparison, and visualization.
Datasets Link: Access all datasets here: 
https://drive.google.com/drive/folders/15STki6abWKQBPIuFJ2IGBP2AeX_P5mjs?usp=sharing

# Key Features
End-to-End Colab Workflow: Every notebook is designed for Google Colab, enabling direct integration with Google Drive for dataset management and results reproducibility.
Diverse Dataset Coverage: Nine datasets ranging from small (e.g., Ionosphere, Air Quality) to extra-large (e.g., Gene Cancer, Amazon Reviews) for robust comparative analysis.
Algorithm Implementation: Custom code for SDS, RFE, PCA, and MI, with notebooks including pseudocode and implementation comments.
Benchmarking: Comparative performance metrics include classification/regression accuracy, R² scores, feature count, and computational efficiency for each method and dataset.

# Results
SDS consistently reduced dimensionality with equal or better model accuracy compared to classical methods.
Visualizations and tables in the notebooks show the impact of feature selection on performance and computation time.
Findings and insights reviewed and benchmarked in the dissertation.


# All datasets are available in the shared Google Drive folder:
https://drive.google.com/drive/folders/15STki6abWKQBPIuFJ2IGBP2AeX_P5mjs?usp=sharing

# Citation and Reference
Code and experiments adhere to the MSc Data Science curriculum of Universaity Of Greenwich.
Please cite the MSc dissertation or refer to the supervisor, Dr. Mohammad Majid Al-Rifaie, if using the methodology or code in academic work.
