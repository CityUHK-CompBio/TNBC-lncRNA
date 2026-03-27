## LINC01235 orchestrates EMT and cancer stemness in triple-negative breast cancer via PEG10 stabilization and extracellular vesicle-mediated signaling   

### 1. Background
Triple-negative breast cancer (TNBC) is the most aggressive subtype of breast cancer. Although extensive transcriptomic profiling has been performed, no systematic analysis has integrated subtype-specific long non-coding RNAs (lncRNAs) to identify drivers of aggressive phenotypes using network-based approaches.

### 2. Major findings   
Here, we conducted a comprehensive analysis of breast cancer transcriptomes and constructed a multi-dimensional regulatory network, which revealed LINC01235 as a master regulator of epithelial-to-mesenchymal transition (EMT) specifically in TNBC. LINC01235 is markedly upregulated in TNBC and associated with poor prognosis. Functional studies demonstrate that LINC01235 promotes EMT, cancer stemness, and metastasis in vitro and in vivo. Mechanistically, by coupling CARPID (CRISPR-assisted RNA–protein interaction detection) with transcriptomic analysis, we uncover a novel post-transcriptional axis in which LINC01235 stabilizes PEG10 mRNA through interaction with the ribosomal protein RPL22. Furthermore, LINC01235 and PEG10 are co-packaged into extracellular vesicles (EVs), enabling intercellular propagation of oncogenic signals and enhancing viability and stem-like properties in recipient TNBC cells. Our findings reveal a previously uncharacterized lncRNA-driven EMT regulatory program operating both intracellularly and via EV-mediated communication, providing clinically relevant insights and highlighting the LINC01235–PEG10 axis as a potential therapeutic target in TNBC.

### 3. Codes for data analysis
* Integrative-Network-Analysis.Rmd: Code for developing the TNBC subtype-specific regulatory network using the TCGA-BRCA dataset.   

* TCGA-BRCA-Data-Processing.Rmd: Code for the pre-processing of TCGA-BRCA dataset downloaded from [the University of California Santa Cruz (UCSC) Xena data portal](https://xenabrowser.net/datapages/).     

* Multi-Uni-Cox-Analysis.Rmd: Code for uni-variate and multi-variate Cox analyzing and visualizing.   
