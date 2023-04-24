# Myeloid-derived suppressor-cell dynamics control outcomes in the metastatic niche


### Citation
If you use ModelingMDSCs in your research, please cite [this paper](https://doi.org/10.1158/2326-6066.CIR-22-0617):

J Kreger, ET Roussos Torres, AL MacLean (2023).
Myeloid-derived suppressor cell dynamics control outcomes in the metastatic niche.
**Can Immunol Res**, 10.1158/2326-6066.CIR-22-0617. 

The bioRxiv version is available [here](https://doi.org/10.1101/2022.06.15.496246). 

### Overview 
This repository contains code used in the analysis of myeloid-derived suppressor-cell dynamics (Kreger et al., 2023, Can Immunol Res). The code is written in Julia (tested on versions 1.6.2 and 1.8.1) and is presented in a Jupyter notebook (Modeling_MDSCs.ipynb). Code blocks within the Jupyter notebook are intended to be run independently. 

Data used in the analysis is included in the file (tumor_data.xlsx). This data is from Spigel, D. R. et al. FIR: Efficacy, Safety, and Biomarker Analysis of a Phase II Open-Label Study of Atezolizumab in PD-L1–Selected Patients With NSCLC. Journal of Thoracic Oncology 13, 1733–1742 (2018). URL [https://www.jto.org/article/S1556-0864(18)30603-8/fulltext](https://www.jto.org/article/S1556-0864(18)30603-8/fulltext) and was also used for mathematical modeling (Study 1) in Laleh, N. G. et al. Classical mathematical models for prediction of response to chemotherapy and immunotherapy. PLOS Computational Biology 18, e1009822 (2022). URL [https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1009822](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1009822).

### Requirements 
 - Julia (version 1.6.2) or newer
 - Jupyter notebook

### Package requirements 
 - [DifferentialEquations.jl](https://diffeq.sciml.ai/stable/)
 - [Turing.jl](https://turing.ml/stable/)
 - MCMCChains.jl
 - StochasticDelayDiffEq.jl
 - DiffEqSensitivity.jl
 - DiffEqCallbacks.jl
 - DecisionTree.jl
 - ScikitLearn.CrossValidation
 - ModelingToolkit.jl
 - StatsPlots.jl
 - Distributions.jl
 - Statistics.jl
 - Catalyst.jl
 - ParameterizedFunctions.jl
 - DiffeqJump.jl
 - Plots.jl; pyplot()
 - DataFrames.jl
 - DelimitedFiles.jl
 - CSV.jl
 - JLD.jl

### Project contents
 - `README.md` : this file with information about the repository and [paper](https://doi.org/10.1101/2022.06.15.496246)
 - `Modeling_MDSCs.ipynb` :  Jupyter notebook containing code blocks for all simulations and figures in the paper. Code blocks within the notebook are intended to be run independently. 
 - `Modeling_MDSCs_julia_v1.8.ipynb` :  Jupyter notebook (updated for Julia 1.8) containing code blocks for all simulations and figures in the paper. Code blocks within the notebook are intended to be run independently. 
 - `tumor_data.xlsx` : data used in the analysis, see Spigel, D. R. et al. FIR: Efficacy, Safety, and Biomarker Analysis of a Phase II Open-Label Study of Atezolizumab in PD-L1–Selected Patients With NSCLC. Journal of Thoracic Oncology 13, 1733–1742 (2018). URL [https://www.jto.org/article/S1556-0864(18)30603-8/fulltext](https://www.jto.org/article/S1556-0864(18)30603-8/fulltext) and Laleh, N. G. et al. Classical mathematical models for prediction of response to chemotherapy and immunotherapy. PLOS Computational Biology 18, e1009822 (2022). URL [https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1009822](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1009822).
 - `gillespie.csv` : Gillespie simulation results (see Figure S5)

### Acknowledgments
We would like to thank E.J. Fertig for valuable discussions and guidance, and the Tumor Microenvironment Program at the USC-Norris Comprehensive Cancer Center for their support. We would like to thank all members of the Roussos Torres and MacLean labs for valuable input and discussions. Figures 1A, 5A, & 6A were created with [BioRender](https://biorender.com/).

### Contributors
<a href="https://github.com/maclean-lab/ModelingMDSCs/graphs/contributors">
  <img src="https://contributors-img.web.app/image?repo=maclean-lab/ModelingMDSCs" />
</a>

