---
output:
  html_document: default
  pdf_document: default
---

## About The Project

This data set is [Practical driving examination results for customers](https://data.gov.au/dataset/ds-qld-3f90a4c3-23df-49dc-b243-9a29c0b23dd5/details?q=Practical%20driving) which is provided by local government authority (LGA) of Queensland. It records the license class, booking type, examination results and driver age group from 2005 to 2019.
We divided the project into three parts, the first part focuses on the annual pass rate of different local government authority. 

The second part mainly aims to compare the age group with different license. 

The third part calculates the correlation between the examination results and booking type.




<!-- GETTING STARTED -->
##  Reproducible description

+ We use renv package to store the package version to make it reproducible.

+ In the file, the Relative Path ensures the files can be read in any computer.

+ In git, we work in different branches individually both for latex and flexdashboard. What's more, we also use variety of git tools. For example, git tag, git amend, git log and so on. 

### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/ttsou87/5513Assignment4.git
   ```
2. Install packages
   ```sh
   #install.packages("renv")
   library(renv)
   renv:restore()
   ```
3. Work on project as normal


<!-- USAGE EXAMPLES -->
## Usage

Use this space to show useful examples of how a project can be used. Additional screenshots, code examples and demos work well in this space. You may also link to more resources.



<!-- Tools -->
## Tools for reproducible

+ Github

+ GitKraken Version 7.6.1

+ Rstudio Version 1.4.1106 

+ Atom 

<!-- LIBRARY -->
## Libraries

- library(tidyverse)
- library(readr)
- library(kableExtra)
- library(bookdown)
- library(ggplot2)
- library(fastDummies)
- library(pROC)
- library(broom)
- library(gtools)

## Contact

+ Qian Duan - qdua0005@student.monash.edu
+ Tina Tsou -  ttso0004@student.monash.edu
+ Shaohu Chen - sche0232@student.monash.edu


Project Link: [https://github.com/ttsou87/5513Assignment4](https://github.com/ttsou87/5513Assignment4)


<!-- LICENSE -->
## License

Distributed under the Apache License 2.0 License. See `LICENSE` for more information.

