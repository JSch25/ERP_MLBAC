# ERP_MLBAC

<div align="justify">
This repository provides additional information and code on the paper "Machine Learning-based Enhancement of Access Control in ERP Systems Using Real-world Data". The paper was submitted for EDOC 2025 – 29th International Conference on Enterprise Design, Operations, and Computing.  In the context of access control in ERP systems, a common challenge is to assign the right permissions to users as accurately as possible. This involves two main tasks: regularly reviewing and validating the access rights of existing users, and assigning appropriate initial permissions to new users based on their responsibilities. To support these challenges, machine learning can be applied to predict access decisions. This approach is referred to as Machine Learning-based Access Control (MLBAC).


The folder [Code](https://github.com/JSch25/ERP_MLBAC/tree/70c751c6d08e60cf072fca050a9117f4f2baee3c/Code) contains Python code as Jupyter Notebooks that apply MLBAC on ERP data. For confidentiality reasons, the actual permission data from the two participating companies is not publicly available. Depending on the specific use case, different Jupyter notebooks are provided: The UserSplit notebook focuses on predicting suitable initial permissions for new users, whereas the RandomSplit notebook is designed for evaluating and validating access permissions of existing users. The folder [Results](https://github.com/JSch25/ERP_MLBAC/tree/70c751c6d08e60cf072fca050a9117f4f2baee3c/Code) provides the complementary results. The results are organized in the same structure as the corresponding Jupyter Notebooks. Additionally, extended results related to Section 6.4 are included.
</div>




Shield: [![CC BY-NC 4.0][cc-by-nc-shield]][cc-by-nc]

This work is licensed under a
[Creative Commons Attribution-NonCommercial 4.0 International License][cc-by-nc].

[![CC BY-NC 4.0][cc-by-nc-image]][cc-by-nc]

[cc-by-nc]: https://creativecommons.org/licenses/by-nc/4.0/
[cc-by-nc-image]: https://licensebuttons.net/l/by-nc/4.0/88x31.png
[cc-by-nc-shield]: https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey.svg
