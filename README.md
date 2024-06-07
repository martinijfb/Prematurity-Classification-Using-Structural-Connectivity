# Prematurity Classification Using Structural Connectivity

## Project Overview
This repository contains a Jupyter notebook implementing a machine learning model to classify babies as preterm or term-born based on structural connectivity matrices of brain regions. These matrices represent the connectivity between pairs of brain regions, with 90 regions total, forming symmetric 90x90 matrices with zeros on the diagonal.

## Dataset
The dataset includes:
- `matrices.p`: A 3D numpy array containing the connectivity matrices in pickle format.
- `subject_info.csv`: Contains information on the age at scan and prematurity status of each subject (1 = premature, 0 = term-born).
- `label_names.csv`: Names of the 90 brain regions involved in the study.
