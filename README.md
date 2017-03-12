# CSE artifact

* Who I am: PhD student homed in CSE; experienced health analytics researcher 

* Advisor - Jimeng Sun PhD; since 2014

* Research focus on healthcare informatics / healthcare analytics (**leveraging analytics to derive *actionable insight* for stakeholders including providers, payers and companies**)

* Current work so far with Sunlab: 2 primary-authored papers, 3 second-authored papers, 4+ middle authored papers

* Major topic of focus: solving real-world medical problems segmentation and disease subtyping via **computational phenotyping** from electronic health record data


## 0. Summary

There are several pieces of work in this artifact.

1. Stratification strategy for electronic health records data
2. Computational phenotyping pipeline
3. Computational phenotyping strategy via knowledge guided tensor factorization

## 1. Stratification Strategy

This is a strategy for two high-yield functions of healthcare service providers and/or payers. The analytic pipeline identifies risk factors for developing uncontrolled hypertension, and automatically segments the patients based on these risk factors.

- published in [Journal of Biomedical and Health Informatics 2016](http://ieeexplore.ieee.org/document/7370874/)
- check it out in [/1_stratification_strategy](/1_stratification_strategy)

## 2. Computational Phenotyping Pipeline

Computational phenotyping pipeline that is leveraged for analysis of electronic health records data. The pipeline takes as input event sequence files for co-occurrences of events and returns as output a detailed set of patient phenotypes (segments of patients).

This has been used widely for a vast array of phenotype discovery work, in many projects I have led or consulted.

- segmentation of Asthma patients
- segmentation of ICU patients
- phenotyping pipeline and risk analysis of ICU patients in Columbia University Medical Center
- segmentation of heart failure (Northwestern Univ, etc)

- check it out in [/2_computational_phenotyping_pipeline](/2_computational_phenotyping_pipeline)


Code can also be found [here](https://mysterious-caverns-96374.herokuapp.com/)

## 3. Knowledge guided tensor factorization

This is an algorithm that takes as input a tensor (multi-dimensional array) capturing co-occurrences of disparate events from electronic health records and automatically extracts phenotypes of patients. This algorithm is an improvement upon previous work in that it incorporates knowledge-guided constraint (to incorporate domain knowledge), pairwise constraint (to induce more distinct phenotypes), and completion constraint (for robustness to missing or noisy data). 

- work has been published in [KDD (top worldwide Data Mining conference)](http://www.sunlab.org/files/8414/3896/4657/rubik_kdd2015_camera_ready.pdf)

- check it out in [/3_knowledge_guided_tensor_factorization](/3_knowledge_guided_tensor_factorization)
- the code is published online and can be obtained from Sunlab website. [download code](https://mysterious-caverns-96374.herokuapp.com/)

## Questions

Please contact rchen87@gatech.edu for further questions.




