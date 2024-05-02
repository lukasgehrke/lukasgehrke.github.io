---
layout: page
title: BIDS workshop
permalink: /bids-workshop-neuroergonomics-2024/
nav: true
nav-order: 2
author: "Lukas Gehrke"
---

# BIDS Workshop at Neuroergonomics 2024

Lukas Gehrke, Technical University Berlin, Germany, <https://orcid.org/0000-0003-3661-1973>  
Sein Jeung, Technical University Berlin, Germany, <https://orcid.org/0000-0002-0247-087X>

The Brain Imaging Data Structure (BIDS) is a standard for organizing and describing neuroimaging datasets. It provides a standardized framework for structuring data generated from various neuroimaging modalities, and recently, also motion capture.

![Teaser for thw BIDS Workshop at Neuroergonomics 2024](/assets/img/bids_workshop/bids-workshop-teaser.png){: width="800"}

The goal of this workshop is to empower participants to convert their recorded data from XDF format (labstreaminglayer) to BIDS and tag it with metadata in a way that facilitates data sharing.  
In the first part of the workshop, participants will learn about BIDS, apply a MATLAB based XDF to BIDS converter (optionally on their own data), and prepare the dataset for sharing. In a second part, participants will learn about best practices when submitting their data to remote repositories. To this end, we  supply a template repository and explain its components in a hands-on manner.  
The workshop will close with a group workout on automated composition of a paper's methods section, using BIDS metadata and LLMs.

We will work through a [template BIDS repository](https://github.com/BeMoBIL/bids-example-specification) that will help with specifying metadata in a user-friednly way. Here, all meta data will be specified in separate JSON files, encouraging user to add rich details of the recording environment, participant demographics and hardware specifications. Workshop participants are encouraged to bring their own data and work with it. Alternatively, we will use the publicly available [Prediction Error Dataset](https://openneuro.org/datasets/ds003846/versions/2.0.2).

During the conference, we will use the [Neuroergonomics Discord Server](https://discord.gg/d4RZnkjA) for exchange.

*Keywords:* Reproducibility, BIDS, Data Sharing, Matlab

## Timeline

![Timeline of the BIDS Workshop at Neuroergonomics 2024](/assets/img/bids_workshop/timeline.png){: width="1024"}

## Software Requirements

Matlab 2019 or newer, preferably latest 2024 Version, and the following toolboxes:

- [FieldTrip](https://www.fieldtriptoolbox.org/)
- Some specific functions that will be shared with the attendees: bemobil_xdf2bids, bemobil_bids2set
- [bids-matlab-tools](https://github.com/sccn/bids-matlab-tools)

## References & Recommended Reading

- Niso, Guiomar, Rotem Botvinik-Nezer, Stefan Appelhoff, Alejandro De La Vega, Oscar Esteban, Joset A. Etzel, Karolina Finc, et al. 2022. “Open and Reproducible Neuroimaging: From Study Inception to Publication.” *NeuroImage* 263 (November): 119623.
- Wilkinson, M. D., Dumontier, M., Aalbersberg, I. J., Appleton, G., Axton, M., Baak, A., ... & Mons, B. (2016). The FAIR Guiding Principles for scientific data management and stewardship. Scientific data, 3(1), 1-9.
- Gorgolewski, K. J., Auer, T., Calhoun, V. D., Craddock, R. C., Das, S., Duff, E. P., ... & Poldrack, R. A. (2016). The brain imaging data structure, a format for organizing and describing outputs of neuroimaging experiments. Scientific data, 3(1), 1-9.
- Pernet, C. R., Appelhoff, S., Gorgolewski, K. J., Flandin, G., Phillips, C., Delorme, A., & Oostenveld, R. (2019). EEG-BIDS, an extension to the brain imaging data structure for electroencephalography. Scientific data, 6(1), 103.
- Poldrack, R. A., Markiewicz, C. J., Appelhoff, S., Ashar, Y. K., Auer, T., Baillet, S., ... & Gorgolewski, K. J. (2023). The Past, Present, and Future of the Brain Imaging Data Structure (BIDS). arXiv preprint arXiv:2309.05768.
- Jeung, Sein, Helena Cockx, Stefan Appelhoff, Timotheus Berg, Klaus Gramann, Sören Grothkopp, Elke Warmerdam, et al. 2023. “Motion-BIDS: Extending the Brain Imaging Data Structure Specification to Organize Motion Data for Reproducible Research.” https://doi.org/10.31234/osf.io/w6z79.
