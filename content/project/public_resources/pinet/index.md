---
date: "2022-02-06"
external_link: ""
authors: ["cdrl"]
image:
  caption: 
  focal_point: Smart
links:
- icon: link
  icon_pack: fas
  name: Link
  url: http://www.pinet-server.org/pinet/ptmToModifier
- icon: file-alt
  icon_pack: fas
  name: Paper
  url: https://pubmed.ncbi.nlm.nih.gov/32469073/

title: PiNET
summary: PiNET is a versatile web platform for downstream analysis and visualization of proteomics data,
tags:
- Resources
- Kinase
- Protein
- Network
- Interactions

---


**piNET** is a versatile tool that can be used to annotate, map and analyze a set of peptide moieties, including those with post-translationally modified sites (PTMs), identified (and quantified) by targeted (SRM type), SWATH (discovery) or related mass spectrometry based techniques. Starting from a set of peptides, and optional modifications within those peptides, piNET provides mapping into canonical UniProt protein entries, standardized annotation of modifications using PsiMOD and UNIMOD ontologies, and mapping of the sites of PTMs in the full UniProt entries. Validated modifying enzymes, including protein kinases, acetyl or methyl transferases, that are known to target these PTM sites, are mapped using iPTMnet and Signor. 

For phosphorylation, known kinase - target peptides are also mapped using PhosphoSitePlus, whereas DeepPhos is used to map predicted kinase – target site pairs. These annotations can be visualized using versatile d3 library to provide site specific network and pathways views. The set of proteins (with PTMs mapped) can be further projected onto biological pathways using enrichment analysis and a comprehensive library of biological gene/protein sets through Enrichr, while protein abundance vectors can be compared with LINCS chemical and genetic perturbation signatures through iLINCS.




