# Ouyang_2018
Title: A new two-phase flow model based on coupling of the depth-integrated continuum method and discrete element method. 

Authors: Chaojun Ouyang (cjouyang@imde.ac.cn), Huicong An, Dongpo Wang. 

This folder contains four sub folders, one for the Massflow code ('massflow'), the second for code of the shared-memory dynamic linking library ('share_dll'), the third for body force code ('body_force_dll'), and the last folder is an example that introduces how to use this code.

Massflow: This folder contains the open source code in fortran for computational fluid mechanics programed by doctor Ouyang, which has been successfully applied to several kinds of earth-surface flows (Ouyang et al., 2015a, 2015b, 2017a, 2017b).

Share_dll: This folder contains the code of the CFD-DEM interface module, a shared-memory dynamic linking library in which the processes of the fluid and the solid phases have both access to read and write data, which allows for the implementation of data exchange.

Body_force_dll: This folder contains the code of the body force computation module.

Example: This folder contains the example that introduces how to use this code to establish a project.


