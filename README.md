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
<img src="./figures/Speck_Mean_curvature_distribution_Compartment.png"  title="" width="960" />

<img src="./figures/Speck_Mean_curvature_vs_Graph_level_Compartment.png"  title="" width="960" />

<img src="./figures/Speck_Mean_curvature_vs_Branch_length_Compartment.png" title="" width="960" />

Distribution of the mean curvature of each branch, and relationship between curvature and graph level or branch length for each of the five compartments at Speck dataset. We studied the graph's shape in bifurcating nodes by calculating the local and remote amplitude angles, and found a high mean and a wide range of angles between two branches in each bifurcating node (e.g., mean$\pm$std of local amplitude is (104.19+-32.23), with min-max range of 12.63-174.10). We further studied how branches curve by calculating their mean curvature, and found that there is a trend towards increasing curvature as graph levels increase, and as branch lengths decrease. 

---
<img src="./figures/BraVa_Mean_curvature_distribution_Compartment.png"  title="" width="960" />

<img src="./figures/BraVa_Mean_curvature_vs_Graph_level_Compartment.png"  title="" width="960" />

<img src="./figures/BraVa_Mean_curvature_vs_Branch_length_Compartment.png" title="" width="960" />

Distribution of the mean curvature of each branch and relationship between curvature and graph level or branch length for each of the five compartments of the single subject from BraVa dataset.

---
<p float="left">
<img src="./figures//Speck_LMCA_SingleCase_Option1_reducePercentage=30.png" title="" width="370"/>
<img src="./figures//Speck_LMCA_numOfSegmentsChanged=7_Option1_reducePercentage=70.png" title="" width="370" />
<img src="./figures/Speck_LMCA_SingleCase_Legend_Option1_Cropped.png" title="" width="135" />
</p>

<p float="left">
<img src="./figures//Speck_LMCA_SingleCase_Option2_reducePercentage=30.png" title="" width="370"/>
<img src="./figures//Speck_LMCA_numOfSegmentsChanged=7_Option2_reducePercentage=70.png" title="" width="370" />
<img src="./figures/Speck_LMCA_SingleCase_Legend_Option2_Cropped.png" title="" width="135" />
</p>

<p float="left">
<img src="./figures//Speck_LMCA_SingleCase_Option3_reducePercentage=30.png" title="" width="370"/>
<img src="./figures//Speck_LMCA_numOfSegmentsChanged=7_Option3_reducePercentage=70.png" title="" width="370" />
<img src="./figures/Speck_LMCA_SingleCase_Legend_Option3_Cropped.png" title="" width="135" />
</p>

Pressure difference (shown by the color of the nodes) and flow velocity difference (shown by the color of the edges) before and after the radius of several selected segments are reduced by 30\% (left) or 70\% (right) of Speck LMCA. The selected segments have the value at both its end to be labeled as 1 and are chosen in three different ways: (1) N segments are chosen randomly in the network. (2) N segments are the immediate downstream segments below a random node (mimicking the condition when there is a stroke). (3) N segments are located in a random confined area (mimicking the condition when there is a tumor). 

---
<img src="./figures//perturb_multiple_cases_option1-3_N=3,5,7,10_reducePercentage=70.png" title="" width="800"/>

The distribution of sum of the absolute pressure differences and the sum of pressure differences before and after radius of selected segments in LMCA are reduced. The segments are chosen in three different ways: (1) N segments are chosen randomly in the network; (2) N segments are the immediate downstream segments below a random node (mimicking the condition when there is a stroke); and (3) N segments are located in a random confined area (mimicking the condition when there is a tumor).
