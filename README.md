# Reproducible and Attributeable Materials Science Workflows
[![DOI](https://zenodo.org/badge/544916792.svg)](https://zenodo.org/badge/latestdoi/544916792) 

## Version: 0.1

## Description
This site provides the deidentified data, reproducible analysis and research report of the project on Reproducible and Attributeable Materials Science Workflows. 

## Associated publications
- A preprint version of the work has been posted at MetaArXiv on July 18, 2022. https://doi.org/10.31222/osf.io/93a4e 

- The manuscript is submitted to a peer-reviewed journal in October, 2022.

## Contributors 
- Ye Li, yel@mit.edu

    MIT Libraries, Massachusetts Institute of Technology

    https://orcid.org/0000-0001-8361-6916 

- Sara Wilson, slwilson@mit.edu

    Department of Mechanical Engineering, Massachusetts Institute of Technology

- Micah Altman, escience@mit.edu
    
    Center for Research in Equitable and Open Scholarship, Massachusetts Institute of Technology

    https://orcid.org/0000-0001-7382-6960 


## Licensing
This materials is distributed under a CC BY 4.0 License https://creativecommons.org/licenses/by/4.0/. 

## Cite the project as:
Ye Li, Sara Wilson, Micah Altman. (2022). Reproducible and Attributeable Materials Science Workflows (dataset and research report), Zenodo, https://doi.org/10.5281/zenodo.7158643. 

## Data and file overview 

* `Data-deidentified`:  folder for deidentified and coded interview data
    * `Data-deidentified\collabrator.tsv`: coded data describing collaborators worked with the research group we investigated
    * `Data-deidentified\meta_instrument.tsv`: coded data describing instruments used during their research workflow
    * `Data-deidentified\meta_storage.tsv`: coded data describing how research input and output is handled
    * `Data-deidentified\recent_files.tsv`: file structure and information of data folder from the research group we investigated
    * `Data-deidentified\workflows.tsv`: coded data describing workflows in steps
* `WorkflowsPaper_files`: folder for intermediate PDFs generated for figures in the article
* `figs`: folder for individual figures in PNG format
* `renv`: folder including files to manage project-local R dependency for reproducible analysis 
* `Appendix_InterviewProtocol.md`: a markdown file of the interview protocol used in this study
* **`WorkflowsPaper.Rmd`**: main Rmarkdown file including the R script to analyze and visualize the data in *Data-deidentified* folder and the markdown file for the research report 
* `WorkflowsPaper.pdf`: a PDF of the research report generated from knitting the *WorkflowsPaper.Rmd* in RStudio 
* `author-info-blocks.lua`: A filter file used to convert author info fields
* `reference.bib`: a BibTex file including all references cited in the research report
* `renv.lock`: a file needed to manage project-local R dependency for reproducible analysis 
* `scholarly-metadata.lua`: A filter file used to convert author info fields 

## Methods
Details of the research method on data collection and analysis can be found in the *Data and Methods* section of the research report. 

To run the data analysis and generate the report in PDF:
- Clone/download the project to your local computer
- Open the project in RStudio Desktop (free version of the software available at https://www.rstudio.com/ )
- Run the **WorkflowsPaper.Rmd** using *Knit to PDF* function in RStudio Desktop to generate the report **WorkflowsPaper.PDF** and the PNG figures under the **figs** folder



## Acknowledgement
The authors thank the Professor Rafael Jaramillo at MIT for his commentary and for enabling access to lab records, and the members of the Jaramillo research group for participation in interviews.

The authors thank MIT Libraries for the special fund and support to the project.


