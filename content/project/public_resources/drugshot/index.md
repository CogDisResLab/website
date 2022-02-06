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
  url: https://maayanlab.cloud/drugshot/

title: Drugshot
summary: DrugShot is a search engine that accepts any search term to return a list of small molecules that are mostly associated with the search terms.
tags:
- Resources
- Drug
- Database


---


**DrugShot** is a search engine that accepts any search term to return a list of small molecules that are mostly associated with the search terms. It can be used to identify novel associations between small molecules and biological mechanisms and processes. A free text search is redirected to a PubMed search via the NCBI E-utilities API for retrieving publications that match the search terms. The resulting list of publications is cross-referenced with DrugRIF or AutoRIF to convert PMIDs to lists of small molecules. DrugRIF and AutoRIF enlist associations between publications and small molecules. DrugShot returns the list of small molecules ranked by their frequency of mentions within the publications returned by the search terms. In addition, the returned small molecules from the initial query are supplanted with additional small molecules based on literature co-mentions and L1000 signature similarity.



