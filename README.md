# Fall_22_Capstone_CTCT_Public
This repository contains all code for the CTCL capstone project. Fall 2022. 

## NOTEBOOKS

 There are currently several notebooks of note. They will be addressed by topic of research/purpose of book.

 Firstly, there are two notebooks existing for the purpose of preprocessing only. genetic_df_setup was for the purpose of getting our genetic data formatted to be used more easily and incorporating CADD scores. It is worth reading up on CADD scores a bit here - https://cadd.gs.washington.edu/ - as they are very prevalent in our work. The score csv is very, very, very large and required being read in in chunks (see second to last cell). This notebook takes a long time to run. initial_data_setup has since been deprecated and exists only for purposes of documenting previous ideas.

 There are several notebooks related to SS/MF classification. Two - genetic_classifer_w_results and genetic_classifer_no_results - are largely deprecated with regards to modeling but are still important to understanding the whole project. They show how the csv "stats_by_sample" is generated, which feeds into the most recent models. They also contain "active" code for finding the genetic regions of interests, at the bottom of the notebook. Boosted_methods is also largely deprecated now but shows the first implementation of boosted algorithms. Original Data_Old_Model Training + Tuning_Alex has recent modeling techniques but is based on old data (we have been getting updates throughout the project from institutional collaborators). New_Updated Data_Model Training + Tuning_Alex is the most up-to-date classifer notebook and is the appropriate place to go to see which models are implemented and how they perform on our most up-to-date data. Models without TNMB+lesion+ eosinophils was implemented to see how the models perform without the presence of several key clinical features. Lastly, Models Evaluation (Leave-Out) was implemented to test the generalizability of models. That is, it withholds an institution in the training process and tests on that institution, in order to gain knowledge on how dependent the models are on intra-institutional learning.

 Finally, there are two notebooks on gene-level results. gene_comparison is now deprecated and exists for documentation of earlier methodologies. mutation_testing contains the most recent notebook with permutation testing code.
 
 ### Please note that no datasets are included in this repository as some of our data is concidered sensitive and private.
 
 ## Team Members
George Bingham Reynolds- gbr2114 /n
Adrian Garcia Hernandez - ag4482
Haoyang (Alex) Shen - hs3312
Sung Jun (Kevin) Won - sw3049
Zhaoyu (Lewis) Wu -zw2783

## Sponsor/Mentor
Dr. Itsik Pe'er, Columbia University
Celine Schreidah
