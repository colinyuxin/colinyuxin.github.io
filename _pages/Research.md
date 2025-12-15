---
layout: single
title: "Research"
permalink: /research/
classes: wide
---

## Adaptive Partial Conjunction Hypothesis (APCH)

Pleiotropy is pervasive in genetics and genomics. For example, a single SNP can influence multiple GWAS phenotypes, and a gene can show coordinated or divergent effects across tissues. Statistically, this naturally leads to a *partial conjunction* formulation. We test a composite null so rejection provides evidence that the feature is jointly non-null for a subset of traits or conditions.



<p style="text-align:center; margin: 1.2rem 0;">
  <img src="/images/research/apch.png" alt="APCH figure" style="width: 100%; height: auto; max-width: none;">
</p>
In our recent work with [Prof. Xiaolei Lin](https://xiaolei-lin.github.io/) at Fudan, we propose APCH, an empirical-Bayes approach that learns a joint effect distribution from summary statistics by deconvolving the observed signals to separate shared structure from noise.

- Preprint: [bioRxiv](https://doi.org/10.1101/2025.11.25.690340)  
- Package: [APCH](https://github.com/colinyuxin/APCH)



## Multi-tissue Transcriptomic Responses to Partitioned Polygenic Risk in Type 2 Diabetes

Polygenic scores (PGS) reflect an individual’s overall genetic liability. Linking PGS with transcriptomic readouts can help clarify how inherited risk shapes disease progression. As argued by [Porcu et al. (Nat Commun, 2021)](https://doi.org/10.1038/s41467-021-25805-y), differentially expressed genes often reflect disease-induced rather than disease-causing changes in the transcriptome. Combining PGS with transcriptome data from a “healthy” cohort can therefore highlight molecular activity associated with genetic liability. Moreover, partitioned polygenic scores capture orthogonal components of disease liability (see [Smith et al., Nat Med, 2024](https://doi.org/10.1038/s41591-024-02865-3)). Together with multi-tissue GTEx data, this allows us to study early molecular onset for the same disease across conditions and tissues.



<p style="text-align:center; margin: 1.2rem 0;">
  <img src="/images/research/prs_expression.png" alt="PRS figure" style="width: 100%; height: auto; max-width: none;">
</p>


With [Prof. Xin He](https://xinhelab.org/) at the University of Chicago, we build analysis pipelines that generate comparable pathway themes across tissues and conditions, and we identify insulin-resistance modules that functions across multiple tissues.




---

