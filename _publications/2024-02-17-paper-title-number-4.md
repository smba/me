---
title: "Identifying Performance Changes Across Variants and Versions"
collection: publications
category: conferences
permalink: /publication/2024-02-17-paper-title-number-4
excerpt: 'This paper is about detecting performance changes lurking in the development history of a software system.'
date: 2020-02-17
venue: 'Proceedings of the International Conference on Automated Software Engineering 2020 (ASE 2020)'
paperurl: 'https://sws.informatik.uni-leipzig.de/wp-content/uploads/2020/09/mas_ase_2020.pdf'
citation: 'Stefan Mühlbauer, Sven Apel, and Norbert Siegmund. Identifying Software Performance Changes Across Variants and Versions. Automated Software Engineering (ASE), pages 611–622. ACM, 2020.'
---

We address the problem of identifying performance changes in the evolution of configurable software systems. Finding optimal
configurations and configuration options that influence performance is already difficult, but in the light of software evolution,
configuration-dependent performance changes may lurk in a potentially large number of different versions of the system.
In this work, we combine two perspectives—variability and time into a novel perspective. We propose an approach to identify con-
figuration-dependent performance changes retrospectively across the software variants and versions of a software system. In a nutshell, we iteratively sample pairs of configurations and versions and measure the respective performance, which we use to update a
model of likelihoods for performance changes. Pursuing a search strategy with the goal of measuring selectively and incrementally
further pairs, we increase the accuracy of identified change points related to configuration options and interactions.
We have conducted a number of experiments both on controlled synthetic data sets as well as in real-world scenarios with different software systems. Our evaluation demonstrates that we can pinpoint performance shifts to individual configuration options
and interactions as well as commits introducing change points with high accuracy and at scale. Experiments on three real-world
systems explore the effectiveness and practicality of our approach.
