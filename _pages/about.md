---
permalink: /
title: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am now a PhD candidate studying in Harbin Institute of Technology (Shenzhen). My research interests are in neuroiamge analysis, geometric-based morphometrics and computational neuroanatomy. My current research focuses on the hippocampus, the cognitive center of the human brain. My doctoral project is dedicated to establishing the connection between histology and clinical imaging, aiming to identify early biomarkers of Alzheimer's disease in the local structure of the hippocampus from large-scale clinical imaging. 

Research —— A multi-scale morphological measurement model based on discrete medial axis geometry: Addressing the issue of measuring the thickness of the hippocampal layered folding structure in imaging.
------
Hippocampal atrophy caused by Alzheimer's disease (AD) results from neuronal cell death. In histological studies, layer thickness and width are typically used as metrics for cortical morphology. However, these metrics lack effective measurement methods in hippocampal magnetic resonance imaging (MRI). The radial vector defined in medial axis geometry can represent the radial axis of an object while maintaining the simplicity of linear distance measurement methods used in histological experiments and the reciprocity of Laplace thickness measurement methods. This ensures that each point on the object's boundary has one and only one thickness measurement value. Therefore, based on the theory of medial axis geometry, we propose a new morphological representation and measurement method for the hippocampus obtained from MRI. This method defines metrics such as the overall and subfield thickness, mediolateral width, and anteroposterior length of the hippocampus, achieving a comprehensive and accurate description of hippocampal morphology.

[MR-based spatiotemporal anisotropic atrophy evaluation of hippocampus in Alzheimer's disease progression by multiscale skeletal representation](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC10502645/pdf/HBM-44-5180.pdf)

Research —— The cross-individual Axis-Referenced Morphometric Model (ARMM): Reducing spatial atrophy measurement errors through a unified interior coordinate system of hippocampus.
------
Individual differences in the hippocampus are evident in the curvature of the anteroposterior axis, the proportion of the anterior and posterior regions, and the varying number of digitations in the head. Current research seldom addresses these differences, often relying on general image registration and global surface reparameterization methods. These methods fail to establish anatomically meaningful correspondences in regions with significant individual variability. An effective solution is to create a unified coordinate system based on the intrinsic invariance of hippocampal geometry and anatomy. This study uses the longitudinal lamellar organization inherent in hippocampal anatomy to construct an axis-referenced coordinate system.

[MRI-based Axis-Referenced Morphometric Model corresponding to lamellar organization for assessing hippocampal atrophy in dementia](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC10502645/pdf/HBM-44-5180.pdf)

Research —— Longitudinal axis-Referenced temporal atrophy measurement model: Reducing temporal atrophy measurement errors through smooth deformation modelling.
------
In Alzheimer's disease (AD), hippocampal atrophy progresses slowly and smoothly over time, but current methods for measuring this progression often face issues due to their reliance on independent segmentation and morphological representation. MRI noise can disrupt hippocampal morphology segmentation, particularly in the small hippocampal region, leading to inconsistent deformations across scans of the same subject. Additionally, independent morphological representation methods, which map each observation's surface to a template, can introduce global reparameterization errors and result in inaccurate detection of deformations. To address these problems, this study introduces a geodesic morphological regression-guided longitudinal segmentation method (GeoLongSeg) to improve hippocampal segmentation accuracy in time-series clinical imaging. We also propose a longitudinal ARs-rep representation (LARs-rep) to overcome localization errors caused by independent morphological representations, allowing for more precise measurement of local atrophy sites and the extent of atrophy throughout the disease progression.

[Geodesic shape regression based deep learning segmentation for assessing longitudinal hippocampal atrophy in dementia progression](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC11179422/pdf/main.pdf)
