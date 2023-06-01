[![DOI](https://zenodo.org/badge/533044775.svg)](https://zenodo.org/badge/latestdoi/533044775)
# Inferring time of infection from field data using dynamic models of antibody decay

<sup>1,2,3,*</sup>Benny Borremans, <sup>1</sup>Riley O Mummah, <sup>1</sup>Angela H Guglielmino, <sup>4</sup>Renee L Galloway, <sup>2,5</sup>Niel Hens, <sup>1</sup>K C Prager, <sup>1</sup>James O Lloyd-Smith
	
<b>Affiliations</b>   
<sup>1</sup> Ecology and Evolutionary Biology Department, University of California Los Angeles, United States;   
<sup>2</sup> I-BioStat, Data Science Institute, Hasselt University, Belgium;  
<sup>3</sup> Evolutionary Ecology Group, University of Antwerp, Belgium;  
<sup>4</sup> Centers for Disease Control and Prevention, United States;   
<sup>5</sup> Centre for Health Economic Research and Modelling Infectious Diseases, Vaccine & Infectious Disease Institute, University of Antwerp, Belgium  

<sup>*</sup>Corresponding author: bennyborremans@gmail.com  


## Repository and reuse information   

This open access repository accompanies the article "Inferring time of infection from field data using dynamic models of antibody decay" (Borremans et al.). It provides all data and code needed to repeat the analyses and reproduce the figures.   
When using the code and/or data available here, please refer to the project license and cite the article using the following citation: 

Borremans B. et al. "Inferring time of infection from field data using dynamic models of antibody decay". bioRxiv 2022.     

Bibtex record:    

```
@article{borremans_inferringTOI_2022,
title = {Inferring time of infection from field data using dynamic models of antibody decay},	
journal = {bioRxiv},
author = {Borremans, Benny and Mummah, Riley O and Guglielmino, Angela H and Galloway, Renee L and Hens, Niel and Prager, K C and Lloyd-Smith, James O},	
year = {2022}	
}
``` 

Github repository DOI: 10.5281/zenodo.7995965.   

## Content description  

<i>Antibody decay model fit.Rmd</i>:  R markdown file containing all code needed to reproduce the analyses and figures.    
<i>Antibody-decay-model-fit.html</i>:  R markdown output.   
<i>Antibody_decay_data.RDS</i>:  R data object containing fox antibody data (excluding negative samples preceding the first positive sample).   
<i>Antibody_decay_data_incl_neg.RDS</i>:  R data object containing fox antibody data (including negative samples preceding the first positive sample).   
<i>Function_comparison_post_overall.RDS</i>:  R data object containing parameter estimates for the three different decay functions.   
The R markdown document refers to a number of additional RDS files that were not included here because of size constraints, but can be easily reproduced with the code provided.    



