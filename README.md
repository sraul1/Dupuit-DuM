# Dupuit groundwater model (DuM)
<img src="https://github.com/sraul1/Dupuit-DuM/blob/main/uga.png" align="center" height="100">

![UGA](uga.png)


[Dupuit groundwater model (DuM)](https://github.com/sraul1/Dupuit-DuM) for use in estimating surficial water table position.


## Introduction

Based on Dupuit's equation for flow in phreatic aquifer between parallel rivers. We use a 2-D form of Dupuit's equation and apply it to surface drainage lines:

$$ h_x = \sqrt{h_0^2 + \frac{Nx}K (2L - x) } $$

 The result is an estimate of water table position above some confining layer. We use basic GIS techniques, and easily available public data in order to parameterize DuM. We use normal digital elevation model (DEM) and LiDAR processing techniques as the backbone of our conceptual model, and take approaches from hydrological and stream network analyses, plus recent developments in graph theory, to drive and actual apply our conceptual model in the form of [DuM](https://github.com/sraul1/Dupuit-DuM).

Most of the DEM processing was accomplished using the [TopoToolbox](https://github.com/csdms-contrib/topotoolbox) addin within MATLAB, as was the processing of the surface drainage network, but the model otherwise runs entirely in R. We hope to transition all [DuM](https://github.com/sraul1/Dupuit-DuM) components into R at some point in the future (hopefully within TopoToolbox's framework of portraying stream networks as directed acyclic graphs, moreover as "rooted trees" to take the language commonly used in graph theory discussions). 

Public version of [DuM](https://github.com/sraul1/Dupuit-DuM) will be posted later in 2023. Feel free to reach out to discuss before then. 

## Funding




