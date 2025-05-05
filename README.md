# 🧪 PubChem Molecular Analysis

This project analyzes molecular property data (Molecular Weight, LogP, InChIKey, and SMILES) for selected drug-like compounds using data from PubChem. The objective is to demonstrate real-world data handling, cleaning, and visualization using Python libraries like Pandas, Seaborn, and Matplotlib.

## 📊 Dataset Source

The dataset is fetched directly from PubChem using the PUG REST API:

[Link to Dataset](https://pubchem.ncbi.nlm.nih.gov/rest/pug/compound/cid/2244,1983,702,6322,5957/property/MolecularWeight,LogP,InChIKey,CanonicalSMILES/CSV)

### Compounds Analyzed:
- Aspirin
- Paracetamol
- Ethanol
- Guanidine
- ATP

---

## ✅ Tasks Performed

1. **Data Collection** from PubChem via REST API
2. **Data Inspection & Cleaning**:
   - Renamed columns for readability
   - Rounded numerical values
   - Added compound names for clarity
3. **Data Visualization**:
   - **Scatter plot** of Molecular Weight vs LogP
   - **Bar chart** of LogP across compounds

---

## 📈 Visualization Highlights

- Compounds with higher LogP values are generally more hydrophobic.
- Molecular weight trends help identify drug-likeness and solubility behavior.

---

## 💡 Bonus Insight: Solvent Selection in Drug Development

Understanding **LogP and molecular weight** trends supports selecting appropriate solvents for drug formulation. Hydrophobic compounds (high LogP) are better suited to non-polar solvents, while hydrophilic compounds (low LogP) dissolve better in polar solvents—key for bioavailability and delivery systems.

---

## 🛠️ Tools Used

- Python
- Jupyter Notebook
- Pandas
- Seaborn
- Matplotlib
- PubChem PUG REST API

---

## 📁 File

- `PubChem_Molecular_Analysis.ipynb`: Main Jupyter notebook with data loading, cleaning, and visualization.

---

## 🔗 How to Run

```bash
# Make sure the following libraries are installed:
pip install pandas matplotlib seaborn requests
