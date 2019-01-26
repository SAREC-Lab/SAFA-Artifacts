# SAFA-Artifacts
Safety Assurance Cases (SACs) are increasingly used to guide and evaluate the safety of software-intensive systems. They are used to construct a hierarchically organized set of claims, arguments, and evidence in order to provide a structured argument that a system is safe for use. However, as the size of the system evolves and grows in size, a SAC can be difficult to maintain.  In this paper we utilize design science to develop a novel solution for identifying areas of a SAC that are affected by changes to the system. Moreover, we generate actionable recommendations for updating the SAC, including its underlying artifacts and trace links, in order to evolve an existing safety case for use in a new version of the system.  Our approach, **Safety Artifact Forest Analysis** (SAFA), leverages traceability to automatically compare software artifacts from a previously approved or certified version with a new version of the system. We identify critical changes in the system and visualize them in a Delta View of the two versions. We further provide  actionable recommendations that an analyst or developer can take to evolve the safety case. We evaluate our approach using the [Dronology](http://www.dronology.info) system for monitoring and coordinating the actions of cooperating, small Unmanned Aerial Vehicles. Results from a user study show that SAFA helped users to identify changes that potentially impacted system safety and provided information that could be used to help maintain and evolve a SAC. 

Please also see the preprint of our paper [Leveraging Artifact Trees to Evolve and Reuse Safety Cases](icse_19_safa_preprint.pdf)
(*Ankit Agrawal, Seyedehzahra Khoshmanesh, Michael Vierhauser, Mona Rahimi, Jane Cleland-Huang, Robyn Lutz*)
for additional details.

## Overview

![SAFA Approach](/SAFA_process.png)


## Dataset
|  Hazard   |  Trees |
|:---------:|:--------:|
|UAV-1006|  |[UAV-1006](/UAV-1006.md)|
|UAV-1007|  |[UAV-1007](/UAV-1007.md)| 
|UAV-1009|  |[UAV-1009](/UAV-1009.md)| 
|UAV-1018|  |[UAV-1018](/UAV-1018.md)| 
|UAV-1021|  |[UAV-1021](/UAV-1021.md)| 
|UAV-1031|  |[UAV-1031](/UAV-1031.md)| 
|UAV-1101|  |[UAV-1101](/UAV-1101.md)| 
|UAV-861|   |[UAV-861](/UAV-861.md)| 
|UAV-906|   |[UAV-906](/UAV-906.md)| 
|UAV-931|   |[UAV-931](/UAV-931.md)|
|UAV-945|   |[UAV-945](/UAV-945.md)| 
|UAV-947|   |[UAV-947](/UAV-947.md)| 
|UAV-999|   |[UAV-999](/UAV-999.md)| 

|  Hazard |  Tree V1 | Tree V2 |  Delta Tree |
|:-------:|:--------:|:-------:|:-----------:|
| Haz1... |  [UAV-xxx](/V0_Tree_images/UAV-1006_SafetyTree.png) | UAV-xxx |  Delta Tree |
|   Haz2  |  UAV-xxx | UAV-xxx |  Delta Tree |
| Haz3... |  UAV-xxx | UAV-xxx |  Delta Tree |
| Haz4... |  UAV-xxx | UAV-xxx |  Delta Tree |
| Haz5... |  UAV-xxx | UAV-xxx |  Delta Tree |
| Haz6... |  UAV-xxx | UAV-xxx |  Delta Tree |
| Haz7... |  UAV-xxx | UAV-xxx |  Delta Tree |
| Haz8... |  UAV-xxx | UAV-xxx |  Delta Tree |
| Haz9... |  UAV-xxx | UAV-xxx |  Delta Tree |
|  Haz10  |  UAV-xxx | UAV-xxx |  Delta Tree |
