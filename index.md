# Some cool notebooks about sandy


## ENDF-6 nuclear data file interface

### Collect and process nuclear data files with NJOY
- [Run NJOY to produce PENDF/ACE files](https://nbviewer.jupyter.org/github/luca-fiorito-11/sandy_notebooks/blob/master/notebook_run_njoy.ipynb)

### Apply perturbations
- [Apply custom perturbations to a given cross section using the WIMS69 energy grid](https://nbviewer.org/github/luca-fiorito-11/sandy_notebooks/blob/executed_notebooks/notebook_perturb_pu9_wims_grid.ipynb)
- [Apply a perturbation to a cross section over the entire energy domain](https://nbviewer.org/github/luca-fiorito-11/sandy_notebooks/blob/executed_notebooks/notebook_perturbation_cross_section_whole_energy.ipynb)

### Work with covariance data
- [Create a custom covariance matrix for cross sections](https://nbviewer.jupyter.org/github/luca-fiorito-11/sandy_notebooks/blob/master/custom_covariance_matrix.ipynb)
- [Covariance matrix with reaction cross terms](https://nbviewer.org/github/luca-fiorito-11/sandy_notebooks/blob/executed_notebooks/notebook_process_pu240_xscov.ipynb)
- [Create correlations between decay branching ratios based on conservation laws](https://nbviewer.org/github/luca-fiorito-11/sandy_notebooks/blob/executed_notebooks/notebook_add_correlations_to_sampled_br.ipynb)


## Stochastic sampling

### Theory
- [LL^T decomposition of covariance matrix](https://nbviewer.org/github/luca-fiorito-11/sandy_notebooks/blob/executed_notebooks/notebook_plot_L_matrix.ipynb)
- [Reconstructing redundant cross section](https://nbviewer.org/github/luca-fiorito-11/sandy_notebooks/blob/executed_notebooks/notebook_sum_xs.ipynb)
- [Build covariance matrix from xs reconstruction rules](https://nbviewer.org/github/luca-fiorito-11/sandy_notebooks/blob/executed_notebooks/notebook_mf33mt51_not_mf33mt4.ipynb)
- [Apply covariance matrix to i.i.d. samples](https://nbviewer.org/github/luca-fiorito-11/sandy_notebooks/blob/executed_notebooks/notebook_apply_covariance_to_samples.ipynb)
- [Sampling from lognormal multivariate distribution](https://nbviewer.org/github/luca-fiorito-11/sandy_notebooks/blob/executed_notebooks/notebook_sampling_lognormal.ipynb)

### Applications
- [Sampling procedure: produce random ENDF-6 / ACE files](https://nbviewer.org/github/luca-fiorito-11/sandy_notebooks/blob/executed_notebooks_v1.1/notebook_random_files.ipynb)
- [Sampling procedure: fission yields](https://nbviewer.org/github/luca-fiorito-11/sandy_notebooks/blob/executed_notebooks/notebook_IFY_sampling_procedure.ipynb)


## Analysis of nuclear data libraries

### Nubar
- [Delayed nubar in Pu-237](https://nbviewer.jupyter.org/github/luca-fiorito-11/sandy_notebooks/blob/master/notebook_jeff40_pu237_nubar.ipynb)
### Resonance parameters
 - [Preliminary test of section MF2](https://nbviewer.org/github/luca-fiorito-11/sandy_notebooks/blob/executed_notebooks/mf2_tests.ipynb)
 - [Preliminary test of section MF32](https://nbviewer.org/github/luca-fiorito-11/sandy_notebooks/blob/executed_notebooks/Mf32_tests.ipynb)
### Angular distributions
- [Angular distribution for elastic scattering of U-238](https://nbviewer.org/github/luca-fiorito-11/sandy_notebooks/blob/executed_notebooks/notebook_plot_mf4_u238.ipynb)
### Energy distributions
- [Interact with energy distributions of emitted neutrons](https://nbviewer.jupyter.org/github/luca-fiorito-11/sandy_notebooks/blob/master/notebook_pfns.ipynb)
### Fission yields
- [Interact with fission product yields](https://nbviewer.jupyter.org/github/luca-fiorito-11/sandy_notebooks/blob/master/notebook_fy.ipynb)
- [Check differences in FYs between the JEFF-3.3 and JEFF-3.1.1 evaluations](https://nbviewer.jupyter.org/github/luca-fiorito-11/sandy_notebooks/blob/master/notebook_fy_diff_jeff33_vs_jeff311.ipynb)
- [Plot _England and Rider_ evaluated chain fission yields](https://nbviewer.org/github/luca-fiorito-11/sandy_notebooks/blob/executed_notebooks/notebook_chain_fy.ipynb)
- [Retrieve cumulative fission yields for Cs, Sr and Nd from different libraries](https://github.com/luca-fiorito-11/sandy_notebooks/blob/executed_notebooks/notebook_u5_pu9_fys.ipynb)
### Radioactive decay data
- [Interact with decay data](https://nbviewer.jupyter.org/github/luca-fiorito-11/sandy_notebooks/blob/master/notebook_decay.ipynb)
- [Analysis of decay energies for Cs-137/Ba-137m and Sr-90/Y-90 decay chains](https://nbviewer.jupyter.org/github/luca-fiorito-11/sandy_notebooks/blob/master/notebook_decay_heat_sr90_cs137.ipynb)