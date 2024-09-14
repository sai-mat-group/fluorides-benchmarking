# Fluorides-Benchmarking
This repository contains the density functional theory calculated data of all transition metal fluorides (TMFs) considered as part of our research paper that is published in *Physical Review Materials*. The manuscript is available at this [DoI]("https://doi.org/10.1103/PhysRevMaterials.8.093801"). An older version of the manuscript is available at [arXiv]("https://arxiv.org/abs/2401.10832").

The objective of the project was to assess the accuracy of the strongly constrained appropriately normed (SCAN) and its restored regularized version (r<sup>2</sup>SCAN) exchange-correlation functionals in predicting material properties of transition metal fluorides. We also used experimental fluorination enthalpies to derive optimal Hubbard *U* corrections for several 3*d* transition metals.

Each functional folder has designed folders for each transition metal system, within which there are individual folders for individual TMFs. Each TMF folder has key output files and the input structure as well. All calculations in the functional folders correspond to structure relaxations.

The LRU folder contains calculated data from our linear response theory calculations. The voltages_transfer_check folder contains calculations related to checking the transferability of the *U* values determined in this work, via calculating Na-intercalation voltages in ternary transition metal fluorides. We have included the convex hull calculations utilised as transferability checks for our *U* values in the Convex_hull_tranferability_check folder.

Since the vasprun.xml output files, coming out of electronic density of states calculations, are quite heavy, they are not directly available in this repository. You can download them from this zipped <a href="https://indianinstituteofscience-my.sharepoint.com/:u:/g/personal/derejebekele_iisc_ac_in/ESzL4z7xyJ9Eq8Q70GoaH0kBGgVRokZ4IDPih7LyY-VhSg?e=caRfCU">OneDrive link</a>. Please do contact drop an email to the authors of the manuscript in case you are unable to access the OneDrive link or have issues with downloading the file.

In case you use any of the data here, we would appreciate a citation to our manuscript at [DoI]("https://doi.org/10.1103/PhysRevMaterials.8.093801").


