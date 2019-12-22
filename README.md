# BiocSwirl

BiocSwirl is a series of in-depth swirlify generated courses used to teach bioinformatics workflows in R/Bioconductor using an interactive and easy to digest format. This project was the People's Choice Award 

<img src="https://github.com/biocswirl-dev-team/Templates/blob/master/graphics_templates/BiocSwirl_bluegree_Hex.png" img align="center" width="500" height="500">

### Features 
BiocSwirl includes 
- Interactive course material that goes from beginner's steps (package installation and environment setup) to low level, to high level analyses and visualizations
- Example inputs and outputs 
- Course-specific package installations and standardized datasets 
- Ability to start at any point of the course material 
- Ability to save progress
- Compatability with BiocTerm 
- Lightweight install, you can install what you want and included datasets are not large. Processing of data is not resource heavy and so it will work on low spec systems  

Pending:
- Templates to communicate own workflow in notebook style 
- Multilanguage workflow course materials for use with BiocTerm 
- More courses 
- Output checker/"Smart Marker"

### Examples of use (GSE71585 dataset):
- [Low Level Analyses](biocswirl_package/courses/scrna_seq/lessons/low_level/low_level.yaml)   
a. Importing, raw data preprocessing   
b. Alignment  
c. Quality Control   
d. Normalization (with and without spike-ins)  
e. Dimensionality Reduction  
f. Correcting for batch effects  
- [High Level Analyses](biocswirl_package/courses/scrna_seq/lessons/high_level/high_level.yaml)  
a. Clustering methods, exploratory analyses    
b. Cell cycle phase classification from gene expression data  
c. HVG and marker gene identification  
- Visualizations for high-throughput data

### Further reference:
[Vignette](vignettes/package_intro.Rmd) - in progress

### Contributing

We are always looking for pull requests and active contributers, if you are interested in designing a course for us or have a feature in mind please submit an issue before doing a pull request. We are currently looking for help developing on Windows systems, bioinformatics workflows and concepts, and support for even more languages in BiocTerm. 

### Team members:

| Name | GitHub ID | Work done |
| ---- | --------- | --------- |
| Lisa N. Cao | lisancao | User Environment & Interface Development |
| Jackie Lu | jql6 | User Environment & Interface Development (tmux) |
| Jeremy Fan | zhemingfan | User Environment & Interface Development |
| Mariam Arab | mariamarab | User Environment & Installation |
| Kate Tyshchenko | ktyshchenko | Documentation, Course Material |
| Paaksum Wong | paaksum | Course Material (main) |
| Sourav Singh | souravsingh | Course Material |   

[Details about hackseq19 project](github.com/lisancao/biocswirl/biocswirl_dev/hackseq_plan)