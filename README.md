## UCSC Cell Browser

## 1. Assigned Gene and Disease

**Name:** Melon, Kris Bernadette S.

**Asssigned Gene:** AR

**Associated Disease:** Spinal and Bulbar Muscular Atrophy

**Date**: September 25, 2026

## Organ/Tissue Choice and Dataset Information

| **Item Information**     |                                                                                                                                                                                                                                                                                           |
| ------------------------ | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Dataset**              | Human IPSC Astrocyte Neuron – Integrated Neurons                                                                                                                                                                                                                                          |
| **Organ/Tissue**         | Human neuronal cells / nervous system                                                                                                                                                                                                                                                     |
| **Cell Types**           | Excitatory neuron 1.1, Excitatory neuron 4.2, Excitatory neuron 4.3, Excitatory neuron 4.4, Excitatory neuron 4.5, Excitatory neuron 4.6, Excitatory neuron 4.7, Excitatory neuron 4.8, Excitatory neuron 4.9, Excitatory neuron 4.10, Excitatory neuron 4.11, and Excitatory neuron 4.12 |
| **Gene**                 | AR                                                                                                                                                                                                                                                                                        |
| **Reason for Selection** | The nervous system is relevant to spinal and bulbar muscular atrophy (SBMA) because the disease affects motor neurons and causes muscle weakness and atrophy. This dataset allows us to examine AR gene expression in human neuronal cells.                                               |
| **Dataset URL**          | https://cells.ucsc.edu/?ds=ipsc-astrocyte-neuron+int-neurons                                                                                                                    |

<img width="1912" height="860" alt="Screenshot 2026-09-25 071804" src="https://github.com/user-attachments/assets/bb5d2dc4-17d3-47f6-b514-106e6c1d0f49" />

Figure 1. UCSC Cell Browser visualization of the Human IPSC Astrocyte Neuron – Integrated Neurons dataset showing different excitatory neuron cell types.

## 3. Understanding the Cell Map

| **Item**                        | **Information**                                                     |
| ------------------------------- | ------------------------------------------------------------------- |
| **Visualization Type**          | 2D cell-embedding layout                                            |
| **What the Dots Represent**     | Individual cells                                                    |
| **What the Clusters Represent** | Groups of cells with similar characteristics or cell types          |
| **Cell Labels Observed**        | Excitatory neuron 1.1, Excitatory neuron 4.2, Excitatory neuron 4.3 |

## 4. Assigned Gene Expression

| **Part**                                                                      | **Answer**                                                                                                            |
| ----------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------- |
| **a. Assigned gene symbol**                                                   | AR                                                                                                                    |
| **b. Dataset used**                                                           | Human IPSC Astrocyte Neuron – Integrated Neurons                                                                      |
| **c. Is expression widespread, restricted, or low/undetected**                | Low overall and relatively restricted                                                                                 |
| **d. Which cluster(s) appear to contain cells with stronger expression?**     | Excitatory neuron 4.3, Excitatory neuron 4.4, and Excitatory neuron 4.6                                               |
| **e. Which cluster(s) appear to contain little or no detectable expression?** | Excitatory neuron 1.1, Excitatory neuron 4.5, Excitatory neuron 4.7, Excitatory neuron 4.8, and Excitatory neuron 4.9 |

<img width="1357" height="787" alt="Screenshot 2026-09-25 073549" src="https://github.com/user-attachments/assets/de44c346-9a4b-4733-b59f-df13ef8cc5c1" />

Figure 2. UCSC Cell Browser visualization of the Human IPSC Astrocyte Neuron – Integrated Neurons dataset showing different annotated excitatory neuron clusters.

## 5. Cell Types and Clusters

| **Part**                                                              | **Answer**                                                                                                                                                                                                                                                                                                         |
| --------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| **a. Cell type/cluster with the strongest visible expression**        | Excitatory neuron 4.6                                                                                                                                                                                                                                                                                              |
| **b. Another cell type/cluster with detectable expression**           | Excitatory neuron 4.3                                                                                                                                                                                                                                                                                              |
| **c. Cell type/cluster with relatively low or undetected expression** | Excitatory neuron 1.1                                                                                                                                                                                                                                                                                              |
| **d. Is the expression pattern broad or cell-type restricted?**       | Relatively cell-type restricted                                                                                                                                                                                                                                                                                    |
| **e. Biological explanation**                                         | Based on the Human IPSC Astrocyte Neuron – Integrated Neurons dataset, AR expression is low overall and appears in only a small number of cells across the neuronal clusters. The variation in AR expression among clusters suggests that AR expression is not equally distributed across all neuronal cell types. |

<img width="1917" height="851" alt="image" src="https://github.com/user-attachments/assets/1787ca53-3c86-4115-9136-42c4e5fd897e" />

Figure 3. AR gene expression in the Human IPSC Astrocyte Neuron – Integrated Neurons dataset, showing generally low and restricted expression across the excitatory neuron clusters.

## 6. Expression Plot

| **Part**                                                                               | **Answer**                                                                                                                                                                                              |
| -------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **a. Which cells/cluster did you select?**                                             | Excitatory neuron 4.6                                                                                                                                                                                   |
| **b. Does your selected group show higher, lower, or similar expression?**             | Excitatory neuron 4.6 showed detectable AR expression, with **6% of cells expressing AR**.                                                                                                              |
| **c. What does the expression plot add that was not obvious from the UMAP/t-SNE map?** | The dot plot directly shows AR expression across the cell clusters. Color represents average expression, while dot size represents the fraction of cells with detectable (non-zero) expression. This provides quantitative context that is less obvious from the UMAP/t-SNE map alone. |

<img width="828" height="822" alt="image" src="https://github.com/user-attachments/assets/1ca28f74-d4d4-45ff-a035-8cabbdc146e5" />

Figure 4. Dot plot showing AR expression across cell types in the Human IPSC Astrocyte Neuron – Integrated Neurons dataset. Dot color represents average AR expression, while dot size represents the fraction of cells with detectable (non-zero) AR expression.

## 7. Marker Genes

| Item                                                         | Answer                                                                             |
| ------------------------------------------------------------ | ---------------------------------------------------------------------------------- |
| **a. Cluster/cell type examined**                            | Excitatory neuron 4.6                                                              |
| **b. Marker gene 1**                                         | GADD45G                                                                            |
| **c. Marker gene 2**                                         | TMED4                                                                              |
| **d. Marker gene 3**                                         | SNHG8                                                                              |
| **e. Does the assigned gene appear among the marker genes?** | No. AR is detectable in Excitatory neuron 4.6, but it is not listed among the marker genes shown for this cluster. Therefore, AR does not appear to uniquely characterize the Excitatory neuron 4.6 cell type in this dataset. |

<img width="1723" height="740" alt="Screenshot 2026-09-25 090748" src="https://github.com/user-attachments/assets/7f872c92-2779-4ee4-90b6-22fcea823427" />

Figure 5. Cluster marker genes for Excitatory neuron 4.6 in the selected dataset; GADD45G, SNHG8, and TMEM70 are among the highest-ranked marker genes shown for this cluster.

## 8. Disease Gene vs. Marker Gene

| **Item**                                                                                                                       | **Answer**                                                                                                                                                                                                                                                                                                                                           |
| ------------------------------------------------------------------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **a. Assigned disease gene**                                                                                                   | AR                                                                                                                                                                                                                                                                                                                                                   |
| **b. Marker gene**                                                                                                             | GADD45G                                                                                                                                                                                                                                                                                                                                              |
| **c. Which gene shows a more cell-type-restricted expression pattern?**                                                        | GADD45G                                                                                                                                                                                                                                                                                                                                              |
| **d. Which gene appears more broadly expressed?**                                                                              | AR                                                                                                                                                                                                                                                                                                                                                   |
| **e. What does this comparison teach you about the difference between a disease-associated gene and a cell-type marker gene?** | A cell-type marker gene such as GADD45G shows a more characteristic expression pattern in a specific cell population. A disease-associated gene such as AR can be biologically relevant without being specific to one cell type. Therefore, disease-associated genes and cell-type marker genes can have different expression patterns and purposes. |

## 9. Connection to Genome Browser and ClinVar

1. On which chromosome is your assigned gene located? Use your previous UCSC Genome Browser activity.
- Chromosome X (Xq12).
  
2. What disease-associated variant did you examine previously?
- The variant was AR c.2296G>A (p.Ala766Thr), a missense variant that changes alanine to threonine.

3. In the current Cell Browser dataset, which cell type(s) express the gene?
- AR is detectable in the Excitatory neuron 4.6 cell type.
   
4. Does the observed cell expression make biological sense based on what you already know about the gene's function or associated disease? Explain in 3-5 sentences.
- Yes. AR is involved in androgen signaling and is important in many tissues. Since SBMA affects motor neurons and muscles, finding AR expression in a neuronal cell type is biologically reasonable.
  
5. Can this single Cell Browser dataset prove that the gene causes the disease? Explain why or why not.
- No. The dataset only shows where AR is expressed. Additional genetic, functional, and clinical evidence is needed to prove that AR causes the disease.

## 10. Short Reflection

1. What did the UCSC Cell Browser show you that the UCSC Genome Browser could not?
- The UCSC Cell Browser showed which specific cell types express the AR gene and how strongly it is expressed. In contrast, the UCSC Genome Browser focused on the gene's chromosomal location and genetic features.

2. Why can the same gene have different expression levels among different cell types?
- Each cell type has a different role in the body, so it requires different genes to be active. Because of these differences, the expression level of the same gene can vary from one cell type to another.
  
3. Why should you be careful when interpreting a gene that shows zero or very low expression in single-cell data?
- A gene with low or undetectable expression is not necessarily inactive. Sometimes the expression level is too low to be detected, or technical limitations in single-cell sequencing may affect the results.

4. Why is it useful to combine information about genomic location, genetic variants, and cell-specific gene expression?
- Combining these types of information provides a more complete understanding of a gene. It helps show where the gene is located, what variants are associated with it, and in which cell types it is expressed.

5. What was the most interesting observation you made about your assigned gene?
- The most interesting observation was that AR was expressed in the Excitatory neuron 4.6 cluster. This was interesting because AR is involved in androgen signaling and has been linked to SBMA, suggesting a possible connection between its function and neuronal cells.

## References
