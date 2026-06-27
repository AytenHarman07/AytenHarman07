# Hi there, I'm Ayten! 👋 🧬
### Biologist | 2nd Ranked Graduate | Bioinformatics Enthusiast

My biggest passion is understanding molecular mechanisms deep within the cell and analyzing complex biological data. I aim to combine my wet-lab experience with computational bioinformatics to make a difference in medical biology and proteomics.

### 🔬 Projects & Academic Achievements
*   **TÜBİTAK 2209-A Project:** Conducted research on the "Phylogenetic analysis of pathogenic microfungi on *Humulus lupulus*" (Project accepted and currently in the reporting stage).
*   **Academic Rank:** Graduated as the **2nd highest-ranking student** in the Biology department.
*   **Awards & Presentations:** Won **1st place** for my poster presentation at my university. Also, I delivered an oral presentation of my research at the Eskişehir Symposium.

### 🧪 Wet-Lab Skills
I have strong hands-on experience in the laboratory, from planning projects to execution and writing reports.
*   **Techniques:** Microorganism Cultivation, DNA Isolation, PCR, Gel Electrophoresis, Nanodrop and TLC.

### 💻 Bioinformatics & Data Analysis
I love translating biological sequences into meaningful insights using code.
*   **Programming & Tools:** Python, Pandas, Matplotlib. I am actively learning and practicing **Biopython**.
*   **Sequence Analysis:** Using NCBI BLAST and FinchTV.
*   **Current Practice:** Analyzing multiple Fasta files, processing BLAST tables, and visualizing biological data using Python.
* 🧬 My Bioinformatics Portfolio
*[Proteomics Data Visualization](Proteomics_Data_Visualization.ipynb)
*[Bioinformatics Pipeline Analysis](Bioinformatics_Pipeline_Analysis.ipynb)

# 🧬 Central Dogma Simulator: Smart Ribosome Edition

This repository contains a Python-based bioinformatics pipeline that simulates the Central Dogma of Molecular Biology. It demonstrates automated biological data retrieval and biologically accurate computational translation. 
👉 [View Central Dogma Simulator Notebook](https://github.com/AytenHarman07/AytenHarman07/blob/main/Central_Dogma_Simulator.ipynb)

## 🚀 Key Features
* **Automated NCBI Fetching:** Directly connects to the NCBI Nucleotide database via `Bio.Entrez` to download real-world FASTA files (e.g., Human TP53 gene) without manual intervention.
* **Smart Ribosome Logic:** Unlike naive translation scripts, this code scans the mRNA for the canonical Start Codon (`AUG`) to bypass the 5' UTR and establishes the correct reading frame.
* **Accurate Termination:** Utilizes the `to_stop=True` parameter to halt translation at the exact biological Stop Codon, preventing artifact generation.


  ## 🧬Clinical Mutation Hunter (Sequence Alignment)
👉 [Clinical Mutation Hunter Notebook](https://github.com/AytenHarman07/AytenHarman07/blob/main/klinik_mutasyon_avcisi.ipynb) 
As an extension of the Central Dogma pipeline, this repository now includes a custom **Point Mutation Detection** module. 

* **Clinical Simulation:** Fetches the healthy Human TP53 reference gene (2500+ bp) directly from NCBI and computationally simulates a carcinogenic point mutation (G -> T substitution).
* **Digital Sequence Alignment:** Iterates through the entire genomic sequence nucleotide by nucleotide, automatically detecting and reporting the exact coordinate of the divergence without manual visual inspection.
* **Bilingual Approach:** The core logic and codebase are written with Turkish documentation to reflect deep conceptual understanding, while the repository structure maintains global standards.

  # 🧬 Statistical Analysis of Cell Migration (ANOVA & Tukey HSD)

This repository contains a Python script to analyze laboratory data. Specifically, it looks at how different doses of a drug (meclofenamic acid) stop the migration (movement) of LNCaP prostate cancer cells.

## 📚 Reference Paper
The biological concept and the data structure used in this script are inspired by this study:
> **Kanli, A., & Yanar, S. (2022).** *The Effect of Meclofenamic Acid on the Invasion and Migration of LNCaP Prostate Carcinoma Cells.* Acta Medica Nicomedia, 5(3), 143-147. DOI: [10.53446/actamednicomedia.1166837](https://doi.org/10.53446/actamednicomedia.1166837)

## 🧪 What Are These Tests and Why Do We Use Them?
When we do an experiment in the lab, we need to prove that our results are mathematically real, not just a coincidence. We use two main tests in this code:

*   **1. One-Way ANOVA:** This test asks the big question: *"Did changing the drug doses make any significant difference overall?"* It looks at all the groups together.
*   **2. Tukey HSD (Post-Hoc):** If ANOVA says "Yes, there is a difference," Tukey steps in to ask: *"Okay, but exactly WHICH groups are different from each other?"* (For example, is the 60 µM dose different from the Control group? Is 80 µM different from 60 µM?)

## 📊 How to Interpret the Results?
When you run the Python code, you will see some numbers printed on your screen. Here is how to read them simply:

*   **P-value (from ANOVA):** If this number is very small (less than `0.05`), it is great news! It means the drug really works, and the difference in cell migration is scientifically significant. 
*   **Reject = True (from Tukey table):** In the Tukey results table, if you see `True` under the `reject` column, it means we *reject* the idea that the two compared groups are the same. It proves that the specific drug dose successfully and significantly changed the cell behavior compared to the other group.
*   **The Boxplot:** The code also draws a boxplot using the `seaborn` library. You can visually see how the cell migration percentage physically drops when the drug dose increases!


### 🌱 Currently Working On
*   Preparing for my Master's Degree in Medical Biology, focusing on **Proteomics**.
*   Creating data visualization projects with sample biological datasets.

📫 **How to reach me:** harmanayten07@gmail.com
