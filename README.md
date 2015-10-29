# Supplementary data repository

![Cychrus caraboides](img/Cychrus_caraboides.jpg)

This repository holds the supplementary data for the manuscript:

**Pentinsaari, M.**, **Vos, R.A.**, and **Mutanen, M.** In prep. Algorithmic single-locus species delimitation: 
effects of sampling effort, variation and non-monophyly in four methods and 1870 species of beetles.
*Molecular Ecology Resources*

Unless indicated otherwise, all files are made available under the [CC0 license](LICENSE).
Contents:

- **[Datasorter.py](src/Datasorter.py)** - Python script to find clusters in taxonomic data.
  Courtesy of Juhani Hopkins. This script is licensed under the [GPL](src/gpl-3.0.txt).
- **[GMYC.R](src/GMYC.R)** - R script for running GMYC analyses on trees generated with BEAST.
  Courtesy of Mikko Pentinsaari.
- **[Table S1](data/Table_S1.tsv)** - BOLD and GenBank accession data and geographic origin of 
  the analyzed specimens. Tab-separated table, UNIX line breaks.
- **[Table S2](data/Table_S2.tsv)** - Summary of sampling, variation, monophyly and OTU 
  delimitation outcome for each species. Tab-separated table, UNIX line breaks.
- **Maximum clade credibility trees** - Input for GMYC species delimitation, in 
  [NEXUS](http://dx.doi.org/10.1093/sysbio/46.4.590) format, with additional embedded 
  annotations for [FigTree](http://tree.bio.ed.ac.uk/software/figtree/):
  - [Adephaga-Staphyliniformia (remaining)](data/GMYC/Adephaga-Staphyliniformia-remaining_maxCladeCred.nex)
  - [Carabidae](data/GMYC/Carabidae_maxCladeCred.nex)
  - [Cerambycidae](data/GMYC/Cerambycidae_maxCladeCred.nex)
  - [Chrysomelidae](data/GMYC/Chrysomelidae_maxCladeCred.nex)
  - [Coleoptera (remaining)](data/GMYC/Coleoptera-remaining_MaxCladeCred.nex)
  - [Curculionoidea](data/GMYC/Curculionoidea_maxCladeCred.nex)
  - [Dytiscidae](data/GMYC/Dytiscidae_maxCladeCred.nex)
  - [Elateridae-Eucnemidae-Buprestidae](data/GMYC/Elateridae-Eucnemidae-Buprestidae_MaxCladeCred.nex)
  - [Staphylinidae (remaining)](data/GMYC/Staphylinidae-remaining_MaxCladeCred.nex)
  - [Tachyporinae-Aleocharinae](data/GMYC/Tachyporinae-Aleocharinae_maxCladeCred.nex)
- **Maximum likelihood trees** - Input for PTP species delimitation, in 
  [Newick](http://evolution.genetics.washington.edu/phylip/newicktree.html) format:
  - [Adephaga-Staphyliniformia-loput](data/PTP/Adephaga-Staphyliniformia-loput_RAxML_bestTree.dnd)
  - [Carabidae](data/PTP/Carabidae_RAxML_bestTree.dnd)
  - [Chrysomelidae](data/PTP/Chrysomelidae_RAxML_bestTree.dnd)
  - [Coleoptera-loput](data/PTP/Coleoptera-loput_RAxML_bestTree.dnd)
  - [Curculionoidea](data/PTP/Curculionoidea_RAxML_bestTree.dnd)
  - [Dytiscidae](data/PTP/Dytiscidae_RAxML_bestTree.dnd)
  - [Staphylinidae-loput](data/PTP/Staphylinidae-loput_RAxML_bestTree.dnd)
  - [Tachyporinae-Aleocharinae](data/PTP/Tachyporinae-Aleocharinae_RAxML_bestTree.dnd)
