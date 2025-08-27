# 🧬 MOLECULAR DOCKING AND DYNAMIC APPROACH IN SILICO, DRUG REPURPOSING FOR LUNG CANCER BY TARGETING AT PI3Kα
## 📌 Problem Statement  
Cancer is a leading cause of mortality worldwide. **Non-Small Cell Lung Cancer (NSCLC)**, a subtype of lung cancer, is becoming increasingly prevalent and resistant to current treatments.  
- The **PI3Kα pathway** is a critical driver of cell proliferation in NSCLC.  
- Targeting PI3Kα has potential but existing inhibitors are **toxic** and **expensive**.  
- **Drug repurposing** offers a safer, faster, and cost-effective alternative since FDA-approved drugs already have regulatory approval.  

## 🎯 Objective  
To identify **FDA-approved drugs** that can be repurposed as potential PI3Kα inhibitors for NSCLC treatment using **structure-based virtual screening (SBVS)** and computational drug discovery tools.  

## 🛠️ Methodology  
1. **Dataset Preparation**  
   - Target protein: **PI3Kα** (PDB ID: 4l23, co-crystal ligand used)  
   - Ligands: **2509 FDA-approved drugs** imported from DrugBank  

2. **Preprocessing**  
   - Protein preparation: *Protein Preparation Wizard*  
   - Ligand preparation: *LigPrep*  

3. **Virtual Screening & Docking**  
   - Performed **molecular docking**  
   - Top **20 compounds** shortlisted based on docking score  
   - Evaluated using **Prime MM/GBSA ∆G binding energy**  

4. **Molecular Dynamics (MD) Simulation**  
   - Top **3 lead molecules** tested for stability  
   - Assessed via **RMSD**, **RMSF**, and **ligand-protein interactions**  
   - **DBO3147** exhibited the most stable and favorable results  

## 📊 Key Findings  
- Successfully screened **FDA-approved drugs** against PI3Kα target  
- Identified **DBO3147** as a promising candidate for NSCLC therapy  
- Repurposed approach saves **time, cost, and reduces toxicity risks** compared to novel drug development  

## 💡 Conclusion  
This study demonstrates that **in silico drug repurposing** can accelerate discovery of potential anticancer agents. Computational screening identified **DBO3147** as a stable and effective PI3Kα inhibitor candidate for **NSCLC treatment**.  

## 🧪 Tools & Technologies  
- **Protein Preparation Wizard**  
- **LigPrep**  
- **Molecular Docking**  
- **Prime MM/GBSA**  
- **Molecular Dynamics Simulation (MD)**  

