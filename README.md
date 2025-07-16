# Isotropic-Remeshing-InterAngle
This is a project based on a paper "Isotropic Remeshing with Inter-Angle Optimization", accepted by The 13th International Conference on Image and Graphics, ICIG2025.
Created by Chenlei Lv from Shenzhen University. Personal Website: https://aliexken.github.io/

<img width="2217" height="773" alt="F6_mesh" src="https://github.com/user-attachments/assets/f77e2625-03a6-47a1-aa2b-6c5c16d3a8ab" />

## Abstract

As an important metric for mesh quality evaluation, the isotropy property holds significant value for applications such as texture UV-mapping, physical simulation, and discrete geometric analysis. Classical mesh isotropy remeshing methods adjust vertices and edge lengths, which exhibit certain limitations in terms of input data sensitivity, geometric consistency control, and convergence speed. In this paper, we proposes an improved isotropy remeshing solution with inter-angle optimization during mesh editing to enhance shape control capability and accelerate convergence. The advantage of the solution lies in its ability to predict the impact of edge length adjustments on subsequent optimization by monitoring angle transformations. It avoids inefficient editing that may cause performance fluctuations, thereby improving efficiency. Experiments demonstrate that the proposed method effectively improves the overall efficiency of mesh optimization.

## Libiary

PCL 1.13.1: https://github.com/PointCloudLibrary/pcl/releases

VCG: https://github.com/cnr-isti-vclab/vcglib (it has been added into the project)

## EXE

For quick testing, we provide an exe file for remeshing directly.

## Updating

2025/07

The related paper, "Isotropic Remeshing with Inter-Angle Optimization", is accepted by ICIG2025.

The project is released.
