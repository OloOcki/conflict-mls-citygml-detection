# conflict-mls-citygml-detection

[![DOI](https://zenodo.org/badge/422141978.svg)](https://zenodo.org/badge/latestdoi/422141978)

## Implementation overview

The implementation can be divided into several steps:
1. Ray casting (C++) 
2. Comparison of point clouds and city models (FME)
3. Projecting textures to models (FME)
4. Deriving probability scores (FME + R)
5. Geometry and semantic modeling (FME)

*full overview diagram - pending*

## Paper

For the in-depth understanding to not hesitate to check out the paper:

```plain
@article{WysockiRefiningByUnderpasses,
title = {Refinement of semantic 3D building models by reconstructing underpasses from MLS point clouds},
journal = {International Journal of Applied Earth Observation and Geoinformation},
volume = {111},
pages = {102841},
year = {2022},
issn = {1569-8432},
doi = {https://doi.org/10.1016/j.jag.2022.102841},
url = {https://www.sciencedirect.com/science/article/pii/S1569843222000437},
author = {Olaf Wysocki and Ludwig Hoegner and Uwe Stilla},
keywords = {MLS point clouds, Building reconstruction, Semantic 3D building models, Underpasses, Buildings refinement, Bayesian networks, Uncertainty},
}
```

## Contact details

Should you have any further questions do not hesitate to ask me: olaf.wysocki@tum.de
