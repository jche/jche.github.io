---
title: "Caliper Synthetic Matching: Radial Matching with Adaptive Calipers and Local Synthetic Controls"
collection: publications
permalink: /research/scmatch
date: 2022-05-01
venue: ''
paperurl: ''
citation: ''
collaborators: 'Luke Miratrix'
description: "Matching methodology using synthetic controls for local bias correction"
---

Abstract: Matching promises simple and transparent causal inferences for observational data, making it an intuitive and easily explainable approach for many applications. Matching methods “match” treated units to control units with similar covariates, with the goal of achieving joint covariate balance between treated and control units as would be expected in a randomized experiment. In practice, however, standard matching methods often perform poorly compared to more recent approaches such as response-surface modeling and balancing. Finding close matches for treated units becomes particularly challenging when there are many covariates and overlap is low, which can lead to imbalanced matched treatment groups and low effective sample sizes. Building on a host of literatures including synthetic control methods, classic matching approaches, and coarsened exact matching, we propose Caliper Synthetic Matching (CSM) to address challenges with finding quality matches while preserving simple and transparent matching diagnostics. CSM is a radial matching method that utilizes adaptive calipers and locally constructed synthetic controls to adjust for inexact matches. By combining adaptive calipers and synthetic controls, CSM produces data-driven bounds on potential extrapolation biases while exploiting local linearity to interpolate in a principled manner. The local nature of CSM also automatically detects units that are more difficult to match and assesses the degree of overlap in the data, so that bias can be controlled even more strongly in regions of greater overlap. We show that CSM belongs to the monotonic imbalance bounding (MIB) class of matching methods, and that it improves upon the bias bounds for popular MIB methods such as coarsened exact matching. We explore the gains from CSM using an extensive simulation study and demonstrate its use on a real dataset.
