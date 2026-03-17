## TITLE: State-Of-The-Art Genotyping Methods for  Model Organisms: Technologies, Pipelines, and System Genetics Applications (2020-Present)

A review paper covering latest genotyping methods and technologies, their strengths, relative differences, and limitations. Further highlights the role of AI (ML models) and PanGenomics suggestively can play to improve genotyping accuracies, complementing limitations reflected by these traditional methods. 

### Structure 

* main.tex - Root Latex file 
* figures/ - Figures 
* tables/ - Tables  
* references.bib - Bibliography 

### Build Instructions 

```sh 
lualatex main 
biber main # if using biblatex 
lualatex main 
lualatex main 

``` 

### Scope for the review 
#### Inlusion criteria 
- Time range: 2020 to present

- Model organisms:
  - Rats (case study)
  - Kilifish (case study)
  - Mouse
  - Drosophila
  - Arabidopsis
  - Celegans

- Methods: technologies, pipelines, and system genetics applications
  - sequence-based genotyping
  - SNP arrays and/or targeted genotyping
  - reduced representation sequencing
  - genotype calling pipelines
  - genotype-phenotype integration platforms

#### Exclusion Criteria 

- purely human clinical genotyping
- single-study GWAS papers without methodological contribution

