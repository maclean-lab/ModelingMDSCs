# Myeloid-derived suppressor cell dynamics control outcomes in the metastatic niche

### Overview 
This repository contains code used in the analysis of myeloid-derived suppressor cell dynamics for the paper located [here](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1009713). All code is written in Julia (version 1.6.2) and is contained in a Jupyter notebook (Modeling_MDSCs.ipynb). Code blocks within the Jupyter notebook are intended to be run independently. 

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
 - `README.md` : this file with information about the repository and [paper](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1009713)
 - `Modeling_MDSCs.ipynb` :  Jupyter notebook containing code blocks for all simulations and figures in the paper. Code blocks within the notebook are intended to be run independently. 
 - `tumor_data.xlsx` : data used in the analysis, see Spigel, D. R. et al. FIR: Efficacy, Safety, and Biomarker Analysis of a Phase II Open-Label Study of Atezolizumab in PD-L1–Selected Patients With NSCLC. Journal of Thoracic Oncology 13, 1733–1742 (2018). URL [https://www.jto.org/article/S1556-0864(18)30603-8/fulltext](https://www.jto.org/article/S1556-0864(18)30603-8/fulltext) and Laleh, N. G. et al. Classical mathematical models for prediction of response to chemotherapy and immunotherapy. PLOS Computational Biology 18, e1009822 (2022). URL [https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1009822](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1009822).
 - `gillespie.csv` : Gillespie simulation results (see Figure S9)

### Acknowledgments
We would like to thank all members of the Roussos Torres and MacLean labs for valuable input and discussions. Figure 1 in the paper was created with [BioRender](https://biorender.com/).

### Contributors
<a href="https://github.com/maclean-lab/ModelingMDSCs/graphs/contributors">
  <img src="https://contributors-img.web.app/image?repo=maclean-lab/ModelingMDSCs" />
</a>

