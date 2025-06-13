
# Objective of the project
1. To identify 2 or 3 conserved DNA repair genes in Drosophila and Mouse.
2. To map their human orthologs.
3. To analyze their mutation profile in cancer using cBioPortal/COSMIC.
4. To summarize the findings with simple Python-based plots and brief biological interpretation.

# Introduction
Cell growth is normally controlled by the actions of certain genes inside each cell. Cancer begins when cells in the body become abnormal and start to grow out of control. This happens where there are changes in genes that affect cell growth. The main types of genes that play a role in cancer are:
* Oncogenes 
* Tumor suppressor genes
* DNA repair genes
Cancer is often the result of changes in more than one of these types of genes within a cell. For the project we will consider the DNA repair genes only, so to find out the repair genes in Drosophila and Mouse we will first use the Gene Ontology (GO) Knowledge base. Which is the world’s largest source of information on the functions of genes.

# Selection of Dna Repair gene selected for further analysis
The Gene Ontology (GO) knowledgebase is the world's largest source of information on the functions of genes. It is used to retrive the Dna repair genes in Drosophila melanogaster and Mus musculu.
![image](https://github.com/user-attachments/assets/a6b05397-f76f-4898-9dfa-c23c32e8578e)

# Mapping the Human orthologs of selected genes
To map the human orthologs of the selected conserved Dna repair genes, we will use the EMBL-ENSEMBL.
Finding from the above are as follows
![image](https://github.com/user-attachments/assets/4c96c4dc-5c30-4c15-812b-8070ffd0b184)

# Analyzing their mutation Profile in Cancer using cBioportal
For Analyzing mutation profile in cancer lets use cBioportal. C bioportal is an open-source platform that allows for visualization, exploration, and analysis of cancer genomic datasets.
One by one on entering the gene symbol into the query tab we get the following mutation profile.
* PMS2: Total mutation is 3
![image](https://github.com/user-attachments/assets/7439b48f-6031-4ddc-b3b5-0413da4f1591)

* XRCC1: total mutation is 98
![image](https://github.com/user-attachments/assets/aa21da2c-4acf-4df3-8e95-8f2fda1206ac)

* Rad51c: Total mutations are 75
  ![image](https://github.com/user-attachments/assets/c93ea4fe-df77-40a2-98f3-aa65036e5052)

Downloaded the mutation data of all the three genes in TSV format. Further summarizing the findings with the help of python in jupyter notebook.

# Summarizing finding using simple python plots and brief biological interpretation
* Mutation of gene vs cancer type
 a) PMS 2 gene shows the least mutation in comparison to the other two genes. It shows the high mutation in colorectal cancer and very least in hepatobiliary cancer type.
![image](https://github.com/user-attachments/assets/dc05d56b-4742-4b37-bcfb-711fbc6e330c)

b)Shows high mutation in Endometrial Cancer and glioblastoma.
Rad51c shows high counts in Endometrial cancer and melanoma cancer. And shows the least count of patients with pancreatic and sarcoma cancer type.

![image](https://github.com/user-attachments/assets/3617b2bd-763d-4808-9a2b-722fab0fdc67)
![image](https://github.com/user-attachments/assets/30a81ce3-65fc-4238-af47-8284adf356b9)

c)Xrcc1 is showing the high mutation in Endometrial, pancreatic and cervical cancer.
![image](https://github.com/user-attachments/assets/0f66a978-aa5e-4abd-9b0c-faba459241ec)
![image](https://github.com/user-attachments/assets/663891e7-1aaa-457d-a93d-4ff76893b84b)


Xrcc1 is showing the same number of counts in mutation as rad51c. From here we can also deduce that mutation of genes in Rad51c and Xrcc1 can be associated with each other.

Thank you so much.
Any inputs are appreciated.



