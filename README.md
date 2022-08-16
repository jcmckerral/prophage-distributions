# Prophage distributions
Data and notebook of a deep dive analysis into prophage distributions on Genbank.

Prophages mined with the prediction tool Phispy (https://github.com/linsalrob/PhiSpy).

Python version 3.8.13.

Please note that this analysis makes use of R packages, meaning that you will need a working installation of R on your machine (with the following packages: diptest, permute, lattice, spatstat), the python package rpy2, and for your python environment to be configured to find R.

This work also makes use of the GTDB taxonomy and taxa classification tool GTDB-tk. 

If you cite us we encourage you to also cite the following papers:
* Sajia Akhter, Ramy K. Aziz, Robert A. Edwards. [PhiSpy: a novel algorithm for finding prophages in bacterial genomes that combines similarity- and composition-based strategies](https://academic.oup.com/nar/article/40/16/e126/1027055/PhiSpy-a-novel-algorithm-for-finding-prophages-in). Nucl Acids Res 2012; 40 (16): e126. doi: 10.1093/nar/gks406 
* McNair, K., Decewicz, P., Akhter, S., Aziz, R.K., Daniel, S., Edwards, R.A. 2019. PhiSpy. https://github.com/linsalrob/PhiSpy/ doi://10.5281/zenodo.3475717
* Parks, D.H., et al. (2021). [GTDB: an ongoing census of bacterial and archaeal diversity through a phylogenetically consistent, rank normalized and complete genome-based taxonomy](https://academic.oup.com/nar/advance-article/doi/10.1093/nar/gkab776/6370255). <i>Nucleic Acids Research</i>, <b>50</b>: D785–D794.
* Rinke, C, et al. (2021). [A standardized archaeal taxonomy for the Genome Taxonomy Database](https://www.nature.com/articles/s41564-021-00918-8). <i>Nature Microbiology</i>, <b>6</b>: 946–959.
* Parks, D.H., et al. 2020. [A complete domain-to-species taxonomy for Bacteria and Archaea](https://rdcu.be/b3OI7). <i>Nature Biotechnology</i>, https://doi.org/10.1038/s41587-020-0501-8.
* Parks DH, et al. 2018. [A standardized bacterial taxonomy based on genome phylogeny substantially revises the tree of life](https://www.nature.com/articles/nbt.4229). <i>Nature Biotechnology</i>, http://dx.doi.org/10.1038/nbt.4229.
