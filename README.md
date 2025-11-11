# 🧬 TRPV6 Gene-to-Protein and Codon Usage Analysis

## 📘 Project Overview
This project explores the **TRPV6 ion channel gene** (*Homo sapiens*) through a complete *gene-to-protein computational workflow*, integrating **sequence retrieval**, **translation**, and **comparative codon usage analysis** across species. The TRPV6 channel plays a critical role in **calcium transport and cancer biology**, making its codon optimization highly relevant for understanding **membrane protein expression efficiency** and **translational control** in disease.

---

##  Author
**Fakhia Mubashir**  
B.Sc. Zoology | Computational Biology Enthusiast  
Research Focus: Ion Channels • Cancer Biology • Membrane Protein Translation  

 [LinkedIn](https://www.linkedin.com/in/fakhia-mubashir/) | [GitHub](https://github.com/fakhia)

## 🧪 Key Tasks and Outputs

### 1️⃣ Sequence Retrieval & Translation
- Retrieved TRPV6 DNA (RefSeq: NM_018646.6) and protein sequences using **NCBI Entrez (BioPython)**  
- Translated DNA into amino acid sequence and verified integrity  
- **Output:** `trpv6_dna.fasta`, `trpv6_protein.fasta`

### 2️⃣ Codon Usage Profiling
- Computed codon frequencies and visualized trends with **Matplotlib**  
- **Output:** `codon_usage_trpv6.csv`, `codon_usage_plot.png`

### 3️⃣ Comparative Codon Usage (Human vs Mouse)
- Compared codon usage between *Homo sapiens* and *Mus musculus* TRPV6 genes  
- Generated **RSCU heatmaps** to explore evolutionary and translational bias  
- **Output:** `trpv6_codon_compare_human_mouse.csv`, `rscu_compare.png`

### 4️⃣ Codon Bias Metrics
- Calculated **GC3 (43.6%)**, **Effective Number of Codons (ENC ≈ 21.7)**, and **Codon Adaptation Index (CAI ≈ 0.75)**  
- Interpreted results in context of TRPV6’s high translational efficiency and potential overexpression in cancer  
- **Output:** `trpv6_codon_metrics_table.csv`, `trpv6_codon_summary_metrics.csv`

### 5️⃣ Codon Bias vs Protein Expression Correlation
- Analyzed how codon bias affects membrane protein expression  
- Highlighted TRPV6’s codon optimization as a factor in efficient calcium ion channel function  

---

## 🧰 Technical Stack
**Languages & Libraries:**  
Python • BioPython • Pandas • NumPy • Matplotlib  

**Concepts:**  
Comparative Genomics • Codon Usage Bias • Translational Efficiency (CAI, ENC, GC3) • Data Visualization  

---

## 🧫 Relevance to MemBioMed
This project connects **molecular coding bias** with **membrane protein translation**, aligning with *MemBioMed’s* core themes:
- Membrane biology and ion channel regulation  
- Computational modeling in biomedicine  
- Molecular insights into disease mechanisms  

---

## 📁 Repository Structure
