# camhd_floc_model

Notebooks for the analysis and modeling of CamHD data. 

Data used in these scripts can be downloaded here: 
https://drive.google.com/open?id=181KueMUMLMRh15r-vXinCp9iu4MYk7Pn

Reproducibility:
For every result, keep track of how it was produced
Avoid manual data-manipulation steps
Archive the exact versions of all external programs used
Version-control all custom scripts
Record all intermediate results, when possible in standard formats
For analyses that include randomness, note underlying random seeds
Always store raw data behind plots
Generate hierarchical analysis output, allowing layers of increasing detail to be inspected
Connect textual statements to underlying results
Provide public access to scripts, runs, and results
These recommendations suggest a certain structure for a project.

Project Layout
A reproducible single-paper project directory structure might look something like this

README.md

LICENSE

environment.yml

data/intermediate_results.csv

notebooks/process_raw_data.ipynb

notebooks/figure1.ipynb

notebooks/figure2.ipynb

notebooks/helper.py

manuscript/manuscript.tex

Donoho, D. et al. (2009), Reproducible research in computational harmonic analysis, Comp. Sci. Eng. 11(1):8–18, doi: 10.1109/MCSE.2009.15

Sandve et al. (2013) give some specific recommmendations for computational reproducibility.

