# BAGECO 2025 - Metagenomics Workshop

*The material in this repository was developed for the 17th Symposium on Bacterial Genetics and Ecology (BAGECO 2025) and will be presented at the Metagenomics Workshop on 30.06.2025.*

*For any questions regarding the material provided here, please contact:*

*Breno L. S. de Almeida: breno-livio.silva-de-almeida@ufz.de*

---

This repository contains all the workshop materials, including ready-to-run Jupyter Notebooks. You can use them directly in Google Colab (no local installation required). The notebooks cover two classes taught at the workshop:

- [From Microbial Ecology to AI – Basics in Machine learning](https://github.com/brenoslivio/BAGECO2025/blob/main/01_ML_Basics.ipynb)

    - The material consists of:

        1. From Toy Datasets to ML Models

        - Exploratory Data Analysis (EDA)

        - k-Nearest Neighbors (k-NN)

        - Random Forest
        
        - Support Vector Machine (SVM)

        2. Evaluating your models

        - Metrics to consider

        - Cross-validation

        3. Extracting features from biological sequences

        - MathFeature

        - Classification

- [From Sequences to Predictions – End-to-end analysis using BioAutoML](https://github.com/brenoslivio/BAGECO2025/blob/main/02_BioAutoML.ipynb)

    - The material consists of:

        - Demonstration including three use cases:

            - Multi-class prediction of DNA/RNA sequences (more than two classes)

            - Binary classification of protein sequences (two classes)

            - Prediction using structured data

## License

Distributed under the MIT License. See `LICENSE` for more information.

## Acknowledgements

If you use the code for MathFeature in your work, we would appreciate citations to the following paper:

```bash
@article{10.1093/bib/bbab434,
    author = {Bonidia, Robson P and Domingues, Douglas S and Sanches, Danilo S and de Carvalho, André C P L F},
    title = "{MathFeature: feature extraction package for DNA, RNA and protein sequences based on mathematical descriptors}",
    journal = {Briefings in Bioinformatics},
    year = {2021},
    month = {11},
    issn = {1477-4054},
    doi = {10.1093/bib/bbab434},
    url = {https://doi.org/10.1093/bib/bbab434},
    note = {bbab434},
    eprint = {https://academic.oup.com/bib/advance-article-pdf/doi/10.1093/bib/bbab434/41108442/bbab434.pdf},
}
```

If you use the code for BioAutoML in your work, we would appreciate citations to the following paper:

```bash
@article{10.1093/bib/bbac218,
    author = {Bonidia, Robson P and Santos, Anderson P Avila and de Almeida, Breno L S and Stadler, Peter F and da Rocha, Ulisses N and Sanches, Danilo S and de Carvalho, André C P L F},
    title = "{BioAutoML: automated feature engineering and metalearning to predict noncoding RNAs in bacteria}",
    journal = {Briefings in Bioinformatics},
    year = {2022},
    month = {06},
    issn = {1477-4054},
    doi = {10.1093/bib/bbac218},
    url = {https://doi.org/10.1093/bib/bbac218},
    note = {bbac218},
}
```