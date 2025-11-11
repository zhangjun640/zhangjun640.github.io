---
layout: archive
title: "Jun Zhang"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}


**Mobile:** +86 18797521846  
**Email:** 202200300321@mail.sdu.edu.cn  
**Personal homepage:** [https://zhangjun640.github.io/](https://zhangjun640.github.io/)  
**Address:** No. 1500, Shunhua Road, Gaoxin District, Jinan, Shandong Province  

---

##  EDUCATION

**Shandong University**, Jinan, China  
*Bachelor of Engineering in Software Engineering*  
*Sept. 2022 – Jul. 2026 (Expected)*  
**GPA:** 88.03 / 100  

**Major Courses:**  
Advanced Mathematics (96); Linear Algebra (100); Advanced Programming (Bilingual) (90);  
Data Structure (Bilingual) (92); Fundamentals of Machine Learning (96); Database System (Bilingual) (91).  

**Research Interests:**  
Methylation analysis; Machine learning and deep learning; Single-cell transcriptomics;  
Medical image analysis; Multimodal data analysis.  

---

##  PUBLICATIONS

- **Jun Zhang**, Jianbo Qiao, Zhiqun Zhao, Chenglin Yin, Junru Jin, Ding Wang, Wenjia Gao, Leyi Wei* :  
  *Accurate detection and quantification of single-base m6A RNA modification using nanopore signals with multi-view deep learning*,  
  *bioRxiv* 2025.08.04.668591; doi:[https://doi.org/10.1101/2025.08.04.668591](https://doi.org/10.1101/2025.08.04.668591) (*NUCLEIC ACIDS RESEARCH*, Under review)

- Zhiqun Zhao#, **Jun Zhang#**, Guangyu Ji, Zhenzhen Zhou, Yaozong Yang, Fengqi Sun and Haiquan Lu* :  
  *Single-cell transcriptomics reveals spaceflight-induced accelerated aging and impaired recovery in the murine bone marrow.*  
  *npj Microgravity* (Under review)

- Jia Liu#, Zhiqun Zhao#, Guangyu Ji#, Jie Lan#, Yuhong Zhang, Qi Liu, **Jun Zhang**, Yajing Zhang, Guangyao Wei, Fengqi Sun, Yiran Yu, Xiaofeng Jiang, Kai Ji, Qi Mei, Kai Zhang, Zheng Wang* , and Haiquan Lu* :  
  *Metabolic redundancy of fatty acid desaturation and elongation promotes hypoxia-induced breast cancer stem cell enrichment.*  
  *Submitted*

---

##  RESEARCH EXPERIENCES
https://github.com/zhangjun640/zhangjun640.github.io/blob/master/_pages/cv.md
### Prediction of RNA Modifications using Nanopore Direct RNA Sequencing Reads  
**Research Assistant**, Research Center of Software and Data Engineering  
*Jun. 2023 – Aug. 2025*

- Processed all raw Nanopore Fast5 files, including base calling, re-squiggle operations, and signal-level analysis, with methylation site information fully extracted. Conducted site-level analysis of RNA methylation data, achieving accurate prediction of methylation sites.  
- Applied Multi-view Model to improve the accuracy of RNA methylation prediction, achieving over 5% improvement compared to m6Anet in HEK293T dataset, providing a valuable tool for better predictions.
- Applied Multi-view Model to improve accuracy by over 5% vs m6Anet on HEK293T dataset.  
- The core output of this project has been submitted as a manuscript to **NUCLEIC ACIDS RESEARCH** (Under review).

---

### Single-cell analysis of the impact of age on immune dysregulation and recovery induced by spaceflight  
**Research Assistant**, Cheeloo College of Medicine  
*Jul. 2024 – Aug. 2025*

- Processed the single-cell sequencing data of OSD-402 and OSD-403 from NASA GeneLab, completing all single-cell analyses including quality control, clustering, cell type annotation, subgroup annotation, cell communication, and pseudotime analysis. 
- Utilized Seurat, monocle3, and other R packages to perform all of the above analyses.
- The core output of this project has been submitted as a manuscript to **npj microgravity** (Under review).

---

### Metabolic redundancy of fatty acid desaturation and elongation promotes hypoxia-induced breast cancer stem cell enrichment  
**Research Assistant**, Cheeloo College of Medicine  
*Jul. 2024 – Mar. 2025*

- Performed functional analysis such as GO, KEGG, GSEA and GSVA to identify critical pathways influenced by hypoxia.  
- Used the Random Forest algorithm to analyze transcriptomics of hypoxia and normoxia groups, recognizing the hypoxia-associated breast cancer hypoxia signature. 
- The core output of this project has been submitted as a manuscript to **Science Bulletin** (Submitted).

---

### Accurate Prediction of Different RNA Modification Types and Their Interactions Using Nanopore Direct RNA Sequencing Reads  
**Research Assistant**, Research Center of Software and Data Engineering  
*Jun. 2025 – Present*

- Discovered that modification occurrences are not mutually independent, identifying significant long-range dependencies (most over 100bp, even over 1000bp) between modification sites.  
- Revealed bidirectional cross-talk between m6A and m5C modifications in HEK293T cell lines; observed that knocking out m6A-specific writer enzymes alters m5C modification levels, and vice-versa.
- Currently collaborating with a biological (wet) lab to design experiments for the biological validation of these computationally predicted modification interactions.

---

##  PROJECT EXPERIENCES

### Hospital Medical Management System  
**Project Leader** | *Jun. 2024 – Aug. 2024*  
**Tech Stack:** JavaScript, CSS, HTML, Java, Apache Shiro, MySQL, Vue  

- Led the overall project architecture design and technology selection, implementing a decoupled front-end (Vue.js) and back-end (Spring Boot) solution. 
- Designed and implemented the security framework using Apache Shiro, delivering user authentication, session management, and Role-Based Access Control (RBAC).  
- Developed and managed the core business modules, including backend APIs for drug information, supplier management, inventory (inbound/outbound), and sales statistics.  
- Project is open-source: [GitHub
    Link](https://github.com/zhangjun640/Hospital-Medical-Management-System)

---

### A Fine-tuned Large Model based on DeepSeek for AI-Assisted
Interviews  
**Project Leader** | *Mar. 2025 – Jun. 2025*  
**Tech Stack:** Python, PyTorch, QLoRA, Ollama, HTML, Vue 3  

- Led the creation and open-sourcing of the world\'s largest Chinese interview dataset (150k+ entries) by scraping tech communities and generating high-quality Q&A pairs using multiple LLMs (GPT-4o, DeepSeek), successfully publishing it on Hugging Face.  
- Directed the technology selection and fine-tuning of the AI interviewer LLM. Employed QLoRA (Unsloth) on a DeepSeek base model, training it on the custom dataset to specialize in generating interview questions, follow-ups, and automated scoring. 
- Designed and deployed the project\'s full-stack architecture: built the frontend application (Vue 3) integrating resume editing, AI polishing, and mock interviews; and deployed the fine-tuned model as an HTTP API service using Ollama.  
- Project is open-source: [GitHub
    Link](https://github.com/zhangjun640/AI-interviewers) 
- Chinese interview datasets are open-source: [Hugging Face
    Link](https://huggingface.co/zhangjun640/datasets)

---

##  COMPETITIONS

- **Chinese Mathematics Competitions** — *Second Prize*, Shandong Province District (*Aug. 2022*)  
- **“Blue Bridge Cup” National Software Engineering Competition** — *Third Prize*, Shandong Province (*Apr. 2024*)

---

##  HONORS & AWARDS

- School Aesthetic Education Scholarship  
- First Prize in University Landscape Project Award  
- Outstanding Individual in University Social Practice  
- Outstanding University Practice Report  
- Outstanding University Practice Team  
- Shandong University Academic Scholarship (Third Prize)

---

##  RESEARCH SKILLS

**Programming Languages:** Python, R, SQL, C++, Java  
**Python Packages:** Pandas, Matplotlib, Scipy, Numpy, Scanpy, pysam, ont-fast5-api, PyTorch, cellpath, Scikit-learn, etc.  
**Software & Tools:** Guppy, Excel, HTML, IGV, VSCode, RStudio, PyCharm, etc.  
**Biology Analysis Expertise:**  
- scRNA analysis (Seurat, Scanpy)  
- Spatial transcriptomics analysis  
- Machine learning for biology  
- Functional enrichment (GO, KEGG, GSVA)  
- Clustering and dimensionality reduction for biological data  

---
