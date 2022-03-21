# Proposal - Group 1

Topic: drug discovery

Disease -> Target genes/proteins -> Drug


## Database:
- Disease
  - **Malacards**: human disease database
  - **DisGeNET**: gene-disease associations
  - **KEGG**: a database resource of biological system. Human diseases, disease genes, drugs and ATC code are extracted.
  - **JSNP**: a repository of Japanese SNP data. Diseases, associated SNPs, and disease genes are extracted.
- Drug
  - **ChEMBL**: bioactive molecules with drug-like properties
  - **DrugBank**: drug target
  - **STITCH 4.0**: a database of protein-chemical interactions [16]. Confidence score of chemical (drug) - protein interaction is extracted.
  - **PubChem**: a database of chemical molecules [19]. Chemical ID according to drug number in the KEGG database is extracted.
- Molecular structure
  - **PDB**
- Target protein
  - **Uniprot**
- Side effect:
  - **SIDER 2**: a side effect resource to capture phenotypic effects of drugs [17, 18]. Chemical (drug), ATC code, drug side effect, and its incidence are extracted.



## Cross reference:



## Reference
[Database application model and its service for drug discovery in Model-driven architecture](https://journalofbigdata.springeropen.com/articles/10.1186/s40537-015-0024-1)