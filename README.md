# ArteryNetworkPaperFigures

This repository contains the appendix figures for our [paper](link):

> Paper info

If you find the code useful for your research, please cite our paper:

> Paper reference

# Appendix Figures

<!--- 
![](./figures/ADAN_ParameterFitting.png)

--->




<img src="./figures/ADAN_ParameterFitting.png" alt="(a)" title="(a)" width="960"  />

<p float="left">
<img src="./figures/ADAN_Terminal_pressure_vs_Path_length.png" alt="(b)" title="(b)" width="290"  />
<img src="./figures/ADAN_Simulated_pressure.png" alt="(c)" title="(c)" width="580"  />
</p>

(a) Comparison between simulated pressure and pressure from ADAN on a node-by-node basis with respect to the graph level. Terminating pressures in the simulation are set to be the same as those in the ADAN result. (b) The relationship between pressure from the ADAN result at each node with respect to its path length. It remains an open question as of why there is such a strong relationship between them. (c) Simulated pressure for compartment LMCA for each node with respect to graph level and path length.

---
<img src="./figures/Speck_Flow_Simulation_LMCA.png" alt="(a)" title="(a)" width="960"  />

<img src="./figures/Speck_Flow_Simulation_RMCA.png" alt="(b)" title="(b)" width="960"  />

<img src="./figures/Speck_Flow_Simulation_LPCA.png" alt="(c)" title="(c)" width="960"  />

<img src="./figures/Speck_Flow_Simulation_RPCA.png" alt="(d)" title="(d)" width="960"  />

Fluid flow simulation results of the four compartments (from top to bottom: LMCA/RMCA/LPCA/RPCA) of the Speck arterial network with 150/250 um resolution.

---
<img src="./figures/Speck_Mean_curvature_distribution_Compartment.png"  title="" width="960"/>

<img src="./figures/Speck_Mean_curvature_vs_Graph_level_Compartment.png"  title="" width="960"/>

<img src="./figures/Speck_Mean_curvature_vs_Branch_length_Compartment.png" title="" width="960"/>

Distribution of the mean curvature of each branch, and relationship between curvature and graph level or branch length for each of the five compartments at Speck dataset. We studied the graph's shape in bifurcating nodes by calculating the local and remote amplitude angles, and found a high mean and a wide range of angles between two branches in each bifurcating node (e.g., mean$\pm$std of local amplitude is (104.19$\pm$32.23), with min-max range of 12.63-174.10). We further studied how branches curve by calculating their mean curvature, and found that there is a trend towards increasing curvature as graph levels increase, and as branch lengths decrease. 