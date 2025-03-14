# ChEMBL EGFR Bioactivity Data Acquisition

🔬 **Project Overview**

This project retrieves and processes bioactivity and compound data from the ChEMBL database specifically for the Epidermal Growth Factor Receptor (EGFR kinase) target protein. The resulting dataset, containing molecular properties, IC50 values, and pIC50 scores, serves as a foundation for cheminformatics analysis and drug discovery research.

✅ **Key Steps in This Project:**

* Connect to the ChEMBL database.
* Retrieve target data for EGFR kinase.
* Fetch bioactivity data (IC50 values).
* Preprocess and standardize bioactivity data.
* Retrieve compound information (molecular structures, SMILES).
* Preprocess and standardize compound data.
* Merge bioactivity and compound data.
* Compute pIC50 values for improved analysis.
* Visualize the most potent compounds.
* Freeze the dataset to ChEMBL 27 for reproducibility.

📊 **Dataset Information**

* Source: ChEMBL Database ([https://www.ebi.ac.uk/chembl/](https://www.ebi.ac.uk/chembl/))
* Citation : https://jcheminf.biomedcentral.com/articles/10.1186/s13321-019-0351-x
* Target: Epidermal Growth Factor Receptor (EGFR kinase)
* Features:
    * Molecular properties of compounds.
    * Bioactivity values (IC50).
    * pIC50 scores (-log10(IC50)).
    * SMILES representations of compounds.

⚙️ **Installation & Usage**

🔹 **Clone the Repository**

```bash
git clone [https://github.com/YourUsername/your-repo-name.git](https://www.google.com/search?q=https://github.com/YourUsername/your-repo-name.git)
cd your-repo-name
