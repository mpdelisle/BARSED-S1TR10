# BARSED-S1TR10
SedFoam case setup for sheet flow under a near-breaking transient (details of physical experiment refer to Mieras, 2018, DesignSafe-CI, https://doi.org/10.17603/DS2BW9W). Modeling paper is published in the European Journal of Mechanics - B/Fluids (Delisle et al., 2022; https://doi.org/10.1016/j.euromechflu.2022.07.002).

**How to Simulate**
1. foamCleanPolyMesh
2. blockMesh
3. go to 0 folder: cp -r alpha.org alpha
4. funkySetFields -time 0
5. sedFoam
