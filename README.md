# Ant Social Organization is understandable by the colony’s study
In this GitHub repository, we present the source code used in the analysis of data sets describing the social interactions of three ant colonies observed on three different days.

The main objective of this repository is to provide access to the code, thereby facilitating the verification of the results. Thus, the emphasis is only on providing guidelines for processing each coding file to reproduce the results, without going into details about the motivations and the conclusions.

Each contributor has individually created a coding file,  resulting in a sequencing of tasks that differs from the order presented in the final report. In particular:
## 1.  Clustering:
   Contains the clustering of the ants in different work groups, then it identifies the work done by each group and looks for the work changes of each single ant in the three considered days. Finally, it estimates which ant (for each colony) is the queen among all of them.

   This file does the work related to the following goals presented in the final report: \
     - _Verification of the study's result:_ **Number of clusters**,  **Tendency of the work changes**; \
     - _Justification of the experimantal results:_ **Finding the queen**.

   **To use it, the datasets have to be saved locally. Then in the first part of the code each dataset is imported inserting the local paths in the variables file1, file2... file 9**

