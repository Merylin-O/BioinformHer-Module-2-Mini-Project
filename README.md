# BioinformHer-Module-2-Mini-Project
# 🧬 Evolutionary Analysis of the Hemoglobin Beta (HBB) Gene Across Species

## 📖 Project Description

This bioinformatics project explores the **evolutionary conservation and divergence** of the **Hemoglobin Beta (HBB) gene** across multiple vertebrate species using publicly available tools and databases. Conducted as part of the [BioinformHer](https://github.com/BioinformHER/Module-2-Mini-Project/tree/main) Mini Project – Module 2 Capstone, the project aims to uncover evolutionary relationships by analyzing HBB sequences through sequence alignment, motif analysis, and phylogenetic inference.

The **HBB gene**, which encodes the β-globin subunit of hemoglobin, plays a vital role in oxygen transport in the blood. Due to its essential function, the HBB gene is relatively conserved across species, making it an ideal candidate for studying molecular evolution.

## 🧑‍🔬 Author
**Merylin Wuraola Ogunlola** 
## Supervised By
**[BioinformHer](https://www.linkedin.com/company/bioinformher/)**

Capstone Project for [BioinformHer Mini Project – Module 2](https://github.com/BioinformHER/Module-2-Mini-Project/tree/main)

## 🎯 Objectives

- Retrieve the human HBB gene and identify homologous sequences in other species.
- Use pairwise and multiple sequence alignment to evaluate evolutionary conservation.
- Identify conserved nucleotide motifs using sequence logos.
- Construct and interpret a phylogenetic tree to visualize species relationships based on HBB gene similarity.

## 🛠️ Tools and Databases Used

| Tool / Database | Purpose | Link |
|------------------|---------|------|
| **NCBI GenBank** | Retrieval of DNA sequences | [NCBI GenBank](https://www.ncbi.nlm.nih.gov/) |
| **BLAST (blastn)** | Identification of homologous sequences | [NCBI BLAST](https://blast.ncbi.nlm.nih.gov/Blast.cgi) |
| **EMBOSS Needle** | Pairwise sequence alignment | [EMBOSS Needle](https://www.ebi.ac.uk/Tools/psa/emboss_needle/) |
| **Clustal Omega** | Multiple sequence alignment | [Clustal Omega](https://www.ebi.ac.uk/Tools/msa/clustalo/) |
| **Skylign** | Sequence logo generation | [Skylign](https://skylign.org/) |
| **MEGA X** | Phylogenetic tree construction | [MEGA Software](https://www.megasoftware.net/) |

## 🔬 Methodology

### 1. Sequence Retrieval and Homology Search
- The human HBB gene was retrieved from NCBI GenBank (Accession: **NC_000011.10**).
- BLAST (blastn) was used to search for homologous HBB sequences in species such as chimpanzee, cow, mouse, sheep, pig, and whale.
- Top sequences were selected based on:
  - **High percent identity**
  - **Low E-value**
  - **Sufficient query coverage**

### 2. Pairwise Sequence Alignment
- EMBOSS Needle was used to compare the human HBB gene with:
  - **Chimpanzee** – 98.2% identity, very few gaps (closely related).
  - **Cow** – 61.8% identity, 24.6% gaps (more distantly related).

### 3. Multiple Sequence Alignment (MSA)
- Six selected sequences were aligned using Clustal Omega.
- Conserved regions were identified with `*` symbols and used to understand functionally important segments.

### 4. Sequence Logo Generation
- The aligned sequences were submitted to [Skylign](https://skylign.org/) to generate a **sequence logo**, which graphically shows nucleotide conservation.

### 5. Phylogenetic Tree Construction
- The MSA file was imported into **MEGA X**, and a **Maximum Likelihood Tree** was constructed using the **Tamura-Nei** model with **500 bootstrap replicates**.

## Species Analyzed and Results Summary

| Common Name | Scientific Name            | Accession No.   | % Identity with Human HBB |
|-------------|----------------------------|------------------|----------------------------|
| Chimpanzee  | *Pan troglodytes*          | X02345.1         | 98.71%                     |
| Cow         | *Bos taurus*               | X00376.1         | 81.09%                     |
| Mouse       | *Mus musculus*             | V00722.1         | 79.03%                     |
| Sheep       | *Ovis aries musimon*       | DQ352468.1       | 80.99%                     |
| Whale       | *Balaenoptera borealis*    | MK622932.1       | 84.23%                     |
| Pig         | *Sus scrofa*               | X86791.1         | 81.94%                     |

## 🌳 Phylogenetic Analysis Insights

- **Chimpanzee and Human HBB** genes are nearly identical.
- **Cow and Sheep** form a strongly supported clade (**bootstrap = 100**).
- **Whale** groups with Cow and Sheep at moderate confidence (**bootstrap = 50**).
- **Pig and Chimpanzee** form another clade (**bootstrap = 69**).
- **Mouse** is the most genetically divergent.

## 🧠 Key Learnings and Biological Relevance

- The HBB gene is **highly conserved** across mammals.
- Conserved regions often correspond to **functionally critical domains**.
- Phylogenetic results support classical taxonomy.


## 📚 References

- [NCBI GenBank](https://www.ncbi.nlm.nih.gov/genbank/)
- [Clustal Omega Documentation](https://www.ebi.ac.uk/Tools/msa/clustalo/)
- [EMBOSS Needle User Guide](https://www.ebi.ac.uk/Tools/psa/emboss_needle/)
- [Skylign Logo Generator](https://skylign.org/)
- [MEGA X Manual](https://www.megasoftware.net/)


Thank you for reading to this point. More details are in the uploaded pdf, [HBB_MiniProject_Merylin Wuraola Ogunlola](https://github.com/Merylin-O/BioinformHer-Module-2-Mini-Project/blob/main/HBB_MiniProject_Merylin%20Wuraola%20Ogunlola.pdf)
