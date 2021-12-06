---
title: "Bruggen Lab - Research"
layout: textlay
excerpt: "Bruggen Lab -- Research"
sitemap: false
permalink: /research/
---

# Research

**Subcutaneous adipose tissue: an immunologically active organ**

The immunological functions of subcutaneous adipose tissue (SAT) in the context of skin-based or systemic inflammation is poorly investigated. Therefore, a better understanding of the immunological SAT “reservoir” in humans under homeostatic or inflammatory conditions is necessary.

Our studies include a characterization and functional exploration of the *cellular and molecular immune players in SAT*. We use novel methodologies for spatial phenotyping of skin tissue at the single cell level. To investigate the specific antigens and signaling pathways in SAT, we aim to develop a full thickness skin model consisting of SAT, dermis and epidermis for studying cell-cell interactions and molecular mechanisms.

*Panniculitis* is an ideal model for us to understand the mechansims in SAT inflammation. We are currently investigating the immune cell infiltrates in panniculitis (inflammation of adipose tissue) to gain new insights into its underlying pathomechanisms. A central aspect in exploring this is to understand antigen-presentation in SAT including the type of antigen-presenting cells involved and the nature of antigens presented.

In terms of *therapeutic targeting of SAT inflammation*, we are currently developing epigenetic switches for programmable control of inflammation in collaboration with Kyoto university.

All of the mentioned conditions may be altered in and impacted by obesity. Therefore, modulation of SAT immune responses is a tempting new approach in the future for development of targeted therapies for cutaneous or systemic immune-related diseases.


**ATOPIC DERMATITIS (AD)**

*Atopic Dermatitis: Sub-Saharan Africa vs. Central Europe*
It is already known that the ethnicity plays an important role in the presentation of AD. However, there is a lack of knowledge about possible variations in pathogenesis. In this prospective observational study, we are comparing AD patients and healthy control participants from Zurich and from Moshi, a city in Tanzania. We compare clinical characteristics, immune signatures, barrier proteins, sensitization patterns as well as the nasal, gut and skin microbiome between AD patients and healthy controls in Tanzania and Switzerland. This project is a collaboration between the University Hospital Zurich and the Regional Dermatology Training Centre in Moshi.

*Atopic Dermatitis and Cardiovascular Diseases*
In this multicenter project, we want to further investigate the association between AD  and cardiovascular diseases, as the existing evidence is contradictory. We’d like to answer questions such as: Are AD patients at a higher risk for cardiovascular comorbidities? Does the AD severity play a role? How does a possible connection relate to the presence of atopic comorbidities? We therefore analyze data from the ProRaD study (Prospective Longitudinal Observational Research in Atopic Dermatitis), which includes more than 705 AD patients and 80 healthy control participants and perform targeted high-throughput proteomics analyses. 

*Atopic Dermatitis and Food Allergies / Intolerances*
Many AD patients suffer from concurrent food allergies and even a higher percentage reports food-related exacerbations of their disease. In this project, we want to further explore the potential connection between food sensitization/allergies, food intolerances, nutritional habits and atopic comorbidities in AD patients.

*Prospective Longitudinal Observational Research in Atopic Dermatitis (ProRaD)*
In ProRAD, a study of CK Care (LINK CK CARE WEBSITE/PRORAD), we investigate the mechanisms underlying the natural course, different disease phenotypes and therapy responsiveness in AD and look for new clinically relevant biomarkers as well as new potential therapeutic targets.

# Imaging Mass Cytometry (IMC)

*Imaging Mass Cytometry (IMC)*

***Imaging Mass Cytometry (IMC)***

**Imaging Mass Cytometry (IMC)**

Imaging Mass Cytometry (IMC) is a spatial mass spectrometric approach which provide a comprehensive and multiparametric technique to investigate tissue with special and single cell resolution. This high dimensional tissue imaging system allows us to quantify up to 50 markers on single cells simultaneously with precise spatial resolution. In this technique tissue slices are labeled with metal conjugated antibodies and slides are ablate by laser to initiate a clump of particles which transport with inert gas to the mass spec that quantify the presence of each metal tag in a pixel. IMC-based methods could be applied on paraffine embedded tissue therefor a retrospective analysis with known results could be carried out. We utilize IMC technique in order to study skin tissue’s spatial structure and cellular compound.

![]({{ site.url }}{{ site.baseurl }}/images/respic/IMCoverview.jpeg){: style="width: 70%; float: center; margin: 10px"}


*Analysis*

One of the crucial points in the system biology and immunology in to explore and exploit information from high dimensional datasets, in order to overcome this challenge, we use different statistical and image analysis tools and pipelines for a better fundamental understanding insights into disease. For pre-processing and single-cell segmentation we use ImcSegmentationPipeline and Dockerized multi-channel image processing framework (Steinbock) developed by Bodenmiller group and it is available on their Github repository. After single-cell generation all further analysis is performed using R bioconductor. 

List for software’s and frameworks that we use to analyze our IMC data:

•	histology topography cytometry analysis toolbox (histoCAT), steinbock, cytomapper and imcRtools all avialabe at  (github.com/BodenmillerGroup).

•	CellProfiler (www.cellprofiler.org) cell image analysis software

•	Ilastik (www.ilastik.org) interactive learning and segmentation toolkit

•	DeepCell (https://github.com/vanvalenlab/deepcell-tf) deep learning library for single-cell analysis of biological images

•	Bioconductor an open source software for bioinformatics (www.bioconductor.org/)


![]({{ site.url }}{{ site.baseurl }}/images/respic/imcanalyz.jpeg){: style="width: 70%; float: center; margin: 10px"}


