
# Hi, I’m Meghana 👋  

🎓 **Bioinformatics & Computational Biology (M.S.)** @ University of Delaware  
🌱 Background in **MicroBiology + Botany + Bioinformatics** | 📊 3+ years working with **RNA-Seq, enrichment analysis, and ML**  
💻 I love applying **machine learning** to **genomics, proteomics**, and **healthcare data**. I build reproducible pipelines across **multi-omics (RNA-seq/ChIP-seq/ATAC-seq) for biomedical prediction and biological interpretation**.


---
## Featured Projects

### 1) MYC Multi-Omics Regulatory Map in LUAD (A549) — ChIP-seq + RNA-seq + ATAC-seq
Goal: identify **high-confidence direct MYC targets** by requiring agreement across DNA binding, expression change, and chromatin accessibility.

- **3-layer Integration (main story):** https://github.com/Kusuru-Meghana/LUAD_MYC_3Layer_Integration  
  - Integrates MYC ChIP-seq + siMYC RNA-seq + ATAC-seq to filter out non-functional binding and indirect DE effects.
  - Enrichment highlights MYC control of growth programs (ribosome/RNA processing/cell cycle).

- **Layer 1 — MYC ChIP-seq:** https://github.com/Kusuru-Meghana/LUAD_MYC_ChIPseq  
  - Genome-wide MYC binding landscape + peak annotation + functional enrichment.

- **Layer 2 — siMYC RNA-seq:** https://github.com/Kusuru-Meghana/LUAD_MYC_RNAseq  
  - Differential expression (siMYC vs CTRL) + QC + pathway interpretation.

- **Layer 3 — ATAC-seq:** https://github.com/Kusuru-Meghana/LUAD_MYC_ATACseq  
  - Chromatin accessibility peak calling/annotation to support functional filtering.

- **ChIP + RNA Integration:** https://github.com/Kusuru-Meghana/LUAD_MYC_ChIPseq_RNAseq_Integration  
  - Finds MYC-bound genes that also change with knockdown → “direct-ish” MYC targets.


---
### 2) Lung Adenocarcinoma Somatic Variant Calling (Tumor-Only WGS) — GATK + VEP
**Repo:** https://github.com/Kusuru-Meghana/Lung-Adenocarcinoma-Somatic-Variant-Calling-Tumor-Only-WGS-

- Built an end-to-end, reproducible tumor-only whole-genome somatic variant calling pipeline for lung adenocarcinoma, following GATK Best Practices from raw FASTQ through annotated VCFs using Bash and Linux workflows.[web:24][web:48]  
- Performed alignment (BWA-MEM), duplicate marking (Picard), and somatic variant calling (GATK Mutect2), identifying ~523K candidate variants and filtering to ~452K high-confidence somatic calls.[web:24][web:51]  
- Conducted functional annotation with Ensembl VEP, prioritizing ~4,700 protein-altering and splice-site variants across ~7,800 genes to support biological interpretation of tumorigenic mutations.[web:33][web:38]

---

### 3) Non-Invasive Renal Fibrosis Prediction (KPMP) — ML + SHAP + Pathway Validation
**Repo:** https://github.com/Kusuru-Meghana/Non-Invasive-Fibrosis-ML-Pipeline  
- Built an explainable ML pipeline to predict fibrosis severity using **clinical + plasma biomarkers**, benchmarked against pathology ground truth.
- Compared invasive vs non-invasive feature sets; used **SHAP** to identify top biomarkers; used enrichment (Reactome/KEGG) for biological validation.

---
### 4) Spatial Transcriptomics Analysis of Human Cerebellum (10x Visium)
**Repo:** https://github.com/Kusuru-Meghana/human-cerebellum-spatial-transcriptomics
- Performed end-to-end spatial transcriptomics analysis of human cerebellum tissue using 10x Genomics Visium data, integrating QC, normalization, PCA, and clustering workflows.  
- Demonstrated that gene expression–based clustering alone recovers spatially coherent tissue domains, validating biological structure without spatial priors.  
- Identified spatially distinct transcriptional domains and cluster-specific marker genes using Leiden clustering and differential expression analysis.

---  

### 5) Alzheimer’s Detection from Blood Transcriptomics — ML + SHAP → Compact Gene Signature
**Repo:** https://github.com/Kusuru-Meghana/Alz-Detect---Machine-Learning-on-Blood-Transcriptomics  
- Built an end-to-end pipeline on GEO blood expression data (probe → gene mapping → ML).
- Baseline vs boosted models + SHAP interpretability; distilled into a compact gene-signature style model.

---

### 6) Functional Enrichment Analysis (GO / KEGG / Reactome / GSEA) — End-to-End Interpretation Workflow
**Repo:** https://github.com/Kusuru-Meghana/functional-enrichment  
- Practical enrichment workflows for gene lists, including preprocessing, visualization, and interpretation.
- Focused on extracting biological meaning from differential gene signals.

---

### 7) Childhood Obesity Risk Prediction (NSCH 2020) — Public Health ML
**Repo:** https://github.com/Kusuru-Meghana/childhood-obesity-prediction  
- Predicts obesity risk (binary) from lifestyle + demographic + family factors.
- Includes EDA, feature engineering, and model comparison.

---

## 🔬 Research Experience  

- 🧪 **Caplan Lab (UDel)** – Protein expression profiling + pathway mapping in plants under pathogen stress.  
- 🧬 **Transcriptomic Analysis** – RNA-Seq of spleen vs bone marrow → 967+ DEGs, immune pathway activation.  
- 🧠 **Alzheimer’s Abstract Annotation** – Ontology-based annotation of biomedical abstracts to extract gene-disease associations.  
- 🌿 **Cowpea Field Trials** – Evaluated organic biostimulants, showing a 20% yield increase → published paper.  

---

## 📚 Publications & Contributions  
## Publications & Scholarly Contributions

- **Adekanye, D., Kusuru, M., Caplan, J. L., & Yu, Y. (2025).**  
  *Toward simple, rapid, and deep plant proteome analysis with an in-cell proteomics strategy.*  
  **bioRxiv (preprint)**  
  https://www.biorxiv.org/content/10.1101/2025.10.30.685699v1

- **Kusuru, M. (2024).**  
  *Ecological Adaptability of Orchids in India.*  
  **Journal of Emerging Technologies and Innovative Research**  
  https://www.jetir.org/view?paper=JETIR2412312

- **Kusuru, M., et al. (2023).**  
  *Effect of Bio-stimulants on Growth and Yield of Cowpea (Vigna unguiculata (L.) Walp).*  
  **International Journal of Agriculture and Environmental Research, 9(4)**  
  https://ijaer.in/effect-of-bio-stimulants-on-growth-and-yield-of-cowpea-vigna-unguiculata-l-walp/

- **Kusuru, M. (2024).**  
  *Biocuration of the NURR1 gene (Q06219) related to Parkinson’s Disease.*  
  **UniProt Community Biocuration Project**  
  https://community.uniprot.org/bbsub/bbsubinfo.html?accession=Q06219

---

## 🛠️ Skills  

- **Programming:** Python, R, SQL, Bash  
- **Bioinformatics Tools:** DESeq2, Cytoscape, Enrichr, FastQC, DAVID, STRING  
- **ML/AI:** scikit-learn, XGBoost, SHAP, PyTorch (protein stability models)  
- **Data Analysis & Viz:** PCA, heatmaps, pathway enrichment, matplotlib, Seaborn  
- **Clinical Systems:** EMR/EHR (Point & Click, NextGen) | HIPAA & FERPA compliance  

---

## 📫 Let’s Connect 
- If you’re working on projects in **genomics, transcriptomics, or multi-omics integration**, I’d love to connect and collaborate. 
- 📧 Email: **meghanak@udel.edu**  
- 💼 LinkedIn: [linkedin.com/in/meghanakusuru](https://www.linkedin.com/in/meghanakusuru)  

---

⭐ *Thanks for visiting! Check out my pinned projects above — they’re my proudest work.*  
