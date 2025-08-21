# SEAwise tutorial on risk assessments of fishing impacts on benthic state
This is the source code for the SEAwise tutorial for the assessment of Relative Benthis State (RBS) using métier-specific effort changes from simulated fisheries management scenarios of the SEAwise North Sea case study. The tutorial falls under SEAwise’s work on modelling the impact of fisheries on benthic ecosystems under Work Package 4: Ecological effects of fisheries. 

SEAwise largely built upon the assessment methodology from the ICES Working Group on Fisheries Benthic Impact and Trade-offs ([WGFBIT Github tutorial](https://github.com/ices-eg/FBIT/tree/master/TAF%20-%20ICES%20tutorial)) and applied it to several regional seas ([Van Hoey et al. 2023](https://doi.org/10.11583/DTU.24049767.v1)). SEAwise also connected these benthic impact risk assessments to (1) spatial modelling approaches to evaluate spatial management scenarios (see [Van Hoey et al. 2024](https://doi.org/10.11583/DTU.28078970.v1); Bastardie et al. [2023](https://doi.org/10.11583/DTU.24331198.v1), [2024](https://doi.org/10.11583/DTU.28079429.v1), [2025](https://doi.org/10.3389/fmars.2025.1629180))
and to (2) mixed fisheries models to evaluate effort-related management scenarios developed in a Management Strategy Evaluation framework ([Kempf et al. 2024](https://doi.org/10.11583/DTU.25152662.v1), [2025](https://doi.org/10.11583/DTU.28081649.v1), [Garcia et al. 2025](https://doi.org/10.11583/DTU.29108039.v2))

Three steps will showcase benthic impact risk assessments (WP4) using outputs from effort-related fisheries management scenarios of the mixed fisheries model *FLBEIA* in the North Sea.

1.  Simulating **depletion scenarios** by matching métier resolutions of benthic impact assessments (Benthis-métiers) with fisheries métiers of mixed fisheries models (e.g. NS FBLEIA métiers).

2.  Fast **RBS estimation** for many simulated scenarios using a vectorized methodology from the [terra](https://rspatial.github.io/terra/) package.

3.  Estimation of **MSFD indicators**, relevant for seafloor integrity and based on the relative surface area meeting arbitrary RBS-thresholds.
