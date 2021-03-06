# Genomics_Final_Project
Abstract

Motivation: Through employing high-resolution transcriptional analyses of the mouse endoderm, the authors of the Nature paper The emergent landscape of the mouse gut endoderm at single-cell resolution were able to pinpoint the order and timing of key events in the formation of the primitive gut tube and subsequently in the organogenesis of the respiratory and gastrointestinal systems. Moreover, the high fidelity of their data allowed for the delineation of previously underappreciated sub-states within well-studied cell populations, by elucidating elaborate gene expression trends. Their paper asserts that cells “acquire a transcriptional identity that reflects their future fate and spatial positioning before overt spatial organization,” meaning that transcriptional priming precedes spatial patterning along the embryo. Nevertheless, such priming is not immutable. Cells maintain a degree of plasticity, and hence future study avenues include gaining a detailed understanding of how extrinsic cues (e.g. signaling) affect the transcriptionally prescribed “propensity” for specific cell fates. 
Results: Our team aimed to recreate this analysis via scRNA-seq analysis. By analyzing such data, we produced figures of clusters organized by different categories including cell type and time point which revealed the distinct identities of cells that make up the endoderm. Furthermore, with the Harmony and Palantir algorithms, we visualized the expression of the GATA6 gene across the E3.5 and E4.5 time points, providing support for GATA’s role in inner cell mass lineage specification to primitive endoderm. Finally, we observed the differentiation potential of mouse embryonic development cells and branch probabilities in primitive endoderm and epiblast cell types.

The files included in this repository were used to cluster the entire given dataset provided by the authors by cell type or time point, separate the data based on time points and cluster the time points according to cell types accordingly, compare embryonic and extra embryonic cell types across different time points via a cluster analysis, and implement the aforementioned Harmony and Palantir algorithms to observe gene expression trends as well as infer cell fate.

Packages included are from authors of paper. Links to packages are included here:

Harmony 0.1:https://github.com/dpeerlab/Harmony

Palantir:https://github.com/dpeerlab/Palantir
