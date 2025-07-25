# 🧪 SMILES Reader and Molecule Visualizer using RDKik
This project reads a CSV file containing SMILES strings and molecule IDs (e.g., ChEMBL IDs), converts them into 2D chemical structure images using RDKit, and displays them. Ideal for cheminformatics and drug discovery tasks.
## 📁 Project Structure
## 📚 Requirements

This project runs in **Google Colab**, which already includes:
- Python 3
- RDKit
- Pandas
- Matplotlib (optional)

No local installation required.
## 📝 Input File Format (`molecules.csv`)

Your CSV file should look like this:

| ChEMBLID     | SMILES                        |
|--------------|-------------------------------|
| CHEMBL123456 | CC(=O)OC1=CC=CC=C1C(=O)O       |
| CHEMBL654321 | C1=CC=C(C=C1)C=O              |
## 🚀 How to Use (in Google Colab)

1. **Open the Colab notebook**:  
   [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/)

2. **Upload your CSV file**:
   ```python
   from google.colab import files
   uploaded = files.upload()  # Choose molecules.csv
   Run the main visualization code
   <img width="952" height="170" alt="Screenshot 2025-07-24 165002" src="https://github.com/user-attachments/assets/9a6f96d6-0568-4d07-b2c1-f1781dce97ba" />

  # 🖼️ Example output
  <img width="600" height="600" alt="download" src="https://github.com/user-attachments/assets/1d794333-5b2e-4675-bf26-47be06451064" />

