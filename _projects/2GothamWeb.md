---
layout: post
title: Cosmic Filaments with LSST
description: Work with the Gotham Web Lab
---

Since May 2024, I've worked as a research assistant in the Gotham Web Lab at City University of New York on applied computational research using simulated data for the upcoming Legacy Survey of Space and Time (LSST) at the Vera C. Rubin Observatory. The project focuses on developing and evaluating methods for identifying multi-scale cosmic filaments in realistic, noisy survey data, with particular emphasis on photometric redshift uncertainty and its impact on downstream analysis.

I built Python-based data processing pipelines to ingest simulated galaxy catalogs, apply redshift slicing, perform coordinate transformations, and generate inputs suitable for filament reconstruction using the existing topology-based tool DisPerSE. After reconstruction, I returned filament outputs to Python for visualization, exploratory analysis, and qualitative comparison against three-dimensional filament structures derived from the underlying simulated galaxy positions.

A central part of my work involved systematically varying reconstruction and preprocessing parameters to evaluate how modeling choices—such as redshift binning strategy and uncertainty treatment—shape inferred filament structure and downstream interpretation. Throughout the project, I emphasized transparent validation, careful handling of uncertainty, and workflows designed to scale to LSST-sized datasets.

I work closely with faculty and postdoctoral researchers in the Gotham Web Lab, independently designing and iterating on the data preparation and analysis workflows used in the project. My code for this project is split into three repositories, [one for work on the Rubin Science Platform](https://github.com/sarahedraves/LSST_Data), [one for work on the Dark Energy Science Collaboration NERSC Jupyter Labs instance](https://github.com/sarahedraves/nersc-code), and [one for local analysis of DisPerSe results](https://github.com/sarahedraves/FilamentAnalysis).
