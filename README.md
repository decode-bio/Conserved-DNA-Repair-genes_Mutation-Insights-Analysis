
# Objective of the project
1. To identify 2 or 3 conserved DNA repair genes in Drosophila and Mouse.
2. To map their human orthologs.
3. To analyze their mutation profile in cancer using cBioPortal/COSMIC.
4. To summarize the findings with simple Python-based plots and brief biological interpretation.
---
# Introduction
Cell growth is normally controlled by the actions of certain genes inside each cell. Cancer begins when cells in the body become abnormal and start to grow out of control. This happens where there are changes in genes that affect cell growth. The main types of genes that play a role in cancer are:
* Oncogenes 
* Tumor suppressor genes
* DNA repair genes
Cancer is often the result of changes in more than one of these types of genes within a cell. For the project we will consider the DNA repair genes only, so to find out the repair genes in Drosophila and Mouse we will first use the Gene Ontology (GO) Knowledge base. Which is the world’s largest source of information on the functions of genes.
---
# Selection of Dna Repair gene selected for further analysis
The Gene Ontology (GO) knowledgebase is the world's largest source of information on the functions of genes. It is used to retrive the Dna repair genes in Drosophila melanogaster and Mus musculu.
![image](https://github.com/user-attachments/assets/5402a415-cdcc-46b2-9164-a0d051d2869c)

---
# Mapping the Human orthologs of selected genes
To map the human orthologs of the selected conserved Dna repair genes, we will use the EMBL-ENSEMBL.
Finding from the above are as follows
![image](https://github.com/user-attachments/assets/e597354a-f0ce-412d-819b-56c653e6b576)

---
# Analyzing their mutation Profile in Cancer using cBioportal
For Analyzing mutation profile in cancer lets use cBioportal. C bioportal is an open-source platform that allows for visualization, exploration, and analysis of cancer genomic datasets.
One by one on entering the gene symbol into the query tab we get the following mutation profile.
* PMS2: Total mutation is 3
  ![image](https://github.com/user-attachments/assets/c1c0b349-23b1-4fa6-8e62-5dc191bd0b0f)


* XRCC1: total mutation is 98
  ![image](https://github.com/user-attachments/assets/d1651375-55dd-49fb-a95e-e1399804c697)


* Rad51c: Total mutations are 75
  ![image](https://github.com/user-attachments/assets/2e84d61a-5309-4702-8534-0e0d6c6f51c9)


Downloaded the mutation data of all the three genes in TSV format. Further summarizing the findings with the help of python in jupyter notebook.
---
# Summarizing finding using simple python plots and brief biological interpretation
* Mutation of gene vs cancer type
 a) PMS 2 gene shows the least mutation in comparison to the other two genes. It shows the high mutation in colorectal cancer and very least in hepatobiliary cancer type.
![image](https://github.com/user-attachments/assets/e235db4e-a950-4110-8190-1503949f0b7a)


b)Shows high mutation in Endometrial Cancer and glioblastoma.
Rad51c shows high counts in Endometrial cancer and melanoma cancer. And shows the least count of patients with pancreatic and sarcoma cancer type.
![image](https://github.com/user-attachments/assets/4aa0455a-a04b-44b2-b4cb-0477c106fb4c)
![image](https://github.com/user-attachments/assets/14968d7a-a5be-4984-868b-648567cdf7cb)



c)Xrcc1 is showing the high mutation in Endometrial, pancreatic and cervical cancer.
![image](https://github.com/user-attachments/assets/85c947df-8041-4b53-8501-ce7232657422)
![image](https://github.com/user-attachments/assets/800d5fd8-1f7c-4b2f-930e-8d8ef6b31d33)


Xrcc1 is showing the same number of counts in mutation as rad51c. From here we can also deduce that mutation of genes in Rad51c and Xrcc1 can be associated with each other.

---




