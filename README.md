# MLBAC for EPR Systems

<div align="justify">
This repository contains supplementary material and code for the paper "Machine Learning-based Enhancement of Access Control in ERP Systems Using Real-world Data", submitted to EDOC 2025 – 29th International Conference on Enterprise Design, Operations, and Computing. In ERP systems, ensuring that users receive only the permissions neeeded is a central challenge in access control. This involves two key tasks within Identity Lifecycle Management: (1) assigning appropriate initial permissions to new users based on their responsibilities, and (2) continously reviewing and validating access rights of existing users. To address these tasks, machine learning can be applied to predict access decisions, referred to as Machine Learning-based Access Control (MLBAC).

## Data
The following table illustrates example data used for MLBAC, showing two users (u<sub>1</sub>, u<sub>2</sub>) and their assignments to three permissions (p<sub>1</sub>, p<sub>2</sub>, p<sub>3</sub>). As the data used in the work originates from the SAP ERP systems of real companies, it is not published for reasons of confidentiality. However, the provided code can be used, e.g., with the data used in the [Amazon Employee Access Challenge](https://www.kaggle.com/datasets/lucamassaron/amazon-employee-access-challenge). For this purpose, only the attributes used must be re-specified in the code.

User          | Permission    | Target | User Attributes | Permission Attributes
:---:         | :---:         | :---:  | :---:                         |:---: 
u<sub>1</sub> | p<sub>1</sub> | 0      | user attributes u<sub>1</sub> | permission attributes p<sub>1</sub>
u<sub>1</sub> | p<sub>2</sub> | 1      | user attributes u<sub>1</sub> | permission attributes p<sub>2</sub>
u<sub>1</sub> | p<sub>3</sub> | 1      | user attributes u<sub>1</sub> | permission attributes p<sub>3</sub>
u<sub>2</sub> | p<sub>1</sub> | 1      | user attributes u<sub>1</sub> | permission attributes p<sub>1</sub>
u<sub>2</sub> | p<sub>2</sub> | 0      | user attributes u<sub>2</sub> | permission attributes p<sub>2</sub>
u<sub>2</sub> | p<sub>3</sub> | 1      | user attributes u<sub>2</sub> | permission attributes p<sub>3</sub>
...           | ...           | ...    | ...                           | ...

## Repository Overview
The folder [Code](https://github.com/JSch25/ERP_MLBAC/tree/70c751c6d08e60cf072fca050a9117f4f2baee3c/Code) contains Python code as Jupyter Notebooks that apply MLBAC on ERP data. Depending on the specific task in the Identity Lifecycle Management, different Jupyter notebooks are provided: (1) The UserSplit notebook focuses on predicting initial permissions for new users, whereas (2) the RandomSplit notebook is designed for evaluating and validating permissions of existing users. The folder [Results](https://github.com/JSch25/ERP_MLBAC/tree/aee58dc83353271ce2689132966678ae26560afb/Results) provides the complementary results. The results are organized in the same structure as the corresponding Jupyter Notebooks. Additionally, extended results related to Section 6.4 are included.
</div>

## Licence
Shield: [![CC BY-NC 4.0][cc-by-nc-shield]][cc-by-nc]

This work is licensed under a
[Creative Commons Attribution-NonCommercial 4.0 International License][cc-by-nc].

[![CC BY-NC 4.0][cc-by-nc-image]][cc-by-nc]

[cc-by-nc]: https://creativecommons.org/licenses/by-nc/4.0/
[cc-by-nc-image]: https://licensebuttons.net/l/by-nc/4.0/88x31.png
[cc-by-nc-shield]: https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey.svg
