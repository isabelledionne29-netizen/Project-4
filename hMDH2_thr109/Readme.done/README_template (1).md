# human Malate Dehydrogenase 2
# P40926
# Phosphorylation of Thr85(109)


## Thr109 of mitochondrial Human Malate dehydrogenase 2 was identified as a post-translationally modified site primarily in studies involving mass spectroscopy and site directed mutagenesis, these were conducted in order to understand impacts on enzyme structure and dynamics (Provost et al., 2024). 

# Part 1 from Project 4 report outline (with citations as appropriate)

1. image of the unmodified site
![image of wildtype thr109 site in its unmodified state](images/unmodifiedsite.png)

2. image of modification site
![modified site where thr109 is phosphorylated-->TPO109](images/modifiedsite.png)


## Effect of the sequence variant and PTM on MDH dynamics

Part 3 from the Project 4 report

1. Image of aligned PDB files (no solvent)
![alignment of wildtype (yellow) and modified models (blue)](images/AlignedWmod.png)

2. Image of the site with the aligned PDB files (no solvent)
![alignment of wildtype (yellow) and Mimic Variant model (green)](images/AlignedWmimic.png)

3. Annotated RMSF plot showing differences between the simulations
![The root-mean-square fluctuation (RMSF) plot of the T109D phosphomimetic variant illustrates dynamic residue behavior across hMDH2. Low RMSF values exhibited within the substrate gating loop residues, ( between residues 90 to 110 ) including the active site. Residue 109 shows no peaks or fluctuations, indicating that substitution from Thr109 to Asp109 does not increase loop flexibility or destabilize the region. Key catalytic residues and substrate-binding residues, including Arg104, Arg110, Arg176, Asp173, and His200, also display low RMSF values, demonstrating a preserved and stable structural geometry. Peaks found at the N and C-terminal regions ( near residues 0 and 300), showing the expected behavior of MDH2 simulations. The overall RMSF pattern mirrors wildtype behavior, demonstrating the T109D mimic variant does not reproduce the expected disturbance from phosphorylation, which would show steric hindrance, and changes in loop dynamics. 
](images/RMSF.png)

4. Annotated plots of pKa for the key amino acids
![The predicted pKa values of ionizable residues in the T109D phosphomimetic variant were generated using the pKa calculator in Google Colab. The plot illustrates several localized areas of ionization, including peaks at residues 7 to 14, 52 to 56, and 203 to 296, and smaller peaks at 282 and 287. Fluctuations may correspond to acidic and basic residues involved in electrostatic interactions rather than to the catalytic site itself. There is no pKa shift observed at or near residue 109, indicating that T109D substitution does not alter the electrostatic environment surrounding the substrate gating loop. Essential catalytic residues Arg104, Arg110, Asp172, and position 200 retain pKa values that are consistent with behavior seen in wild-type hMDH2. Illustrates that the T109D mutation does not reproduce the expected consequences of phosphorylation.
](images/pKadata.png)


## Comparison of the mimic and the authentic PTM

Part 4 from the Project 4 report outline
include images as needed
![comparison and overlap of the Mimic variant model (green) and modified phosphorylated model (blue)](images/mimicandPTM.png)

### Colab notebook links
https://colab.research.google.com/drive/1ozLoyvvsyarXcR_p7a_dO3ceAW8Il8SN?usp=sharing

Provide file names of completed colab notebooks



## Authors

Isabelle Dionne
Dr. Berndsen

## Deposition Date
12/2/2025

## License

Shield: [![CC BY-NC 4.0][cc-by-nc-shield]][cc-by-nc]

This work is licensed under a
[Creative Commons Attribution-NonCommercial 4.0 International License][cc-by-nc].

[![CC BY-NC 4.0][cc-by-nc-image]][cc-by-nc]

[cc-by-nc]: https://creativecommons.org/licenses/by-nc/4.0/
[cc-by-nc-image]: https://licensebuttons.net/l/by-nc/4.0/88x31.png
[cc-by-nc-shield]: https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey.svg


## References

* McCue, W. M., & Finzel, B. C. (2021b). Structural characterization of the human cytosolic malate dehydrogenase I. ACS Omega, 7(1), 207–214. https://doi.org/10.1021/acsomega.1c04385  ![10.1021](10.1021/acsomega.1c04385)
* Ban, H. S., Xu, X., Jang, K., Kim, I., Kim, B.-K., Lee, K., & Won, M. (2016). A novel malate dehydrogenase 2 inhibitor suppresses hypoxia-inducible factor-1 by regulating mitochondrial respiration. PLOS ONE, 11(9). https://doi.org/10.1371/journal.pone.0162568  ![10.1371](10.1371/journal.pone.0162568)
* Zhong, Q., Xiao, X., Qiu, Y., Xu, Z., Chen, C., Chong, B., Zhao, X., Hai, S., Li, S., An, Z., & Dai, L. (2023, May 2). Protein posttranslational modifications in health and diseases: Functions, regulatory mechanisms, and therapeutic implications. MedComm. https://pmc.ncbi.nlm.nih.gov/articles/PMC10152985/
 ![10.1002]( 10.1002/mco2.261)
* Eo, Y., Duong, M. T. H., and Ahn, H.-C. (2022, August 25) Structural comparison of HMDH2 complexed with natural substrates and cofactors: The importance of phosphate binding for active conformation and catalysis. Biomolecules. U.S. National Library of Medicine. ![10.3390]( 10.3390/biom12091175)
*  RJ;, D. F. T. Phosphorylation-related modification at the dimer interface of 14-3-3ω dramatically alters monomer interaction dynamics. Archives of biochemistry and biophysics. U.S. National Library of Medicine. 
 ![10.1016]( 10.1016/j.abb.2013.10.025)
* Martínez-Reyes, I., and Chandel, N. S. (2020, January 3). Mitochondrial TCA cycle metabolites control physiology and disease. Nature News. Nature Publishing Group
 ![10.1038](10.1038/s41467-019-13668-3)
* Lyskov, S., Chou, F. C., Conchúir, S. Ó., Der, B. S., Drew, K., Kuroda, D., Xu, J., Weitzner, B. D., Renfrew, P. D., Sripakdeevong, P., Borgo, B., Havranek, J. J., Kuhlman, B., Kortemme, T., Bonneau, R., Gray, J. J., and Das, R. (2013). "Serverification of Molecular Modeling Applications: The Rosetta Online Server That Includes Everyone (ROSIE)". PLoS One, 8(5), e63906. 
![10.1371](10.1371/journal.pone.0063906)
*  Provost, J. J., Cornely, K. A., Mertz, P. S., Peterson, C. N., Riley, S. G., Tarbox, H. J., Narasimhan, S. R., Pulido, A. J., and Springer, A. L. (2024) Phosphorylation of mammalian cytosolic and mitochondrial malate dehydrogenase: Insights into regulation. Essays in Biochemistry 68, 183–198. 
 ![10.1042](10.1042/EBC20230079)
*  MDH2 protein expression summary - the human protein atlas. HPA.  !

