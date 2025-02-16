---
layout: single
title:  "Critical Appraisal of Primary AI Literature in Medicine"
author: Lekaa Rambabu
toc: true
---

# Assessing the risk of bias within primary AI literature in medicine

In medical literature, systematic reviews are considered as the “highest quality of evidence”
in the evidence-based pyramid (EBM) pyramid [^fn1]. A systematic review synthesises
primary literature using a pre-defined eligibility criteria, conducting database searches, and
using tools for critical appraisal to address a specific research question. Once the relevant
studies are identified, they are evaluated for reporting quality and assessed for risk of bias.
This rigorous process helps contextualise the results of the studies, ensuring that the
conclusions are informed by a thorough and critical analysis of the methodologies used in
the primary studies.

![EBM Figure](/assets/images/2024-12-25/critical_practice_guidelines.png)


Research on AI technology in medicine has gained momentum over the last two decades, with indexed articles on PubMed increasing from around 1,000 articles in 2000 to over 50,000 in 2024. In medical imaging, AI models have been reported to be superior or comparable to clinicians in making certain diagnoses however many studies comparing AI versus clinicians are not prospective, not randomised, are at high risk of bias, and deviate from reporting standards [^fn2].
For appraisal of primary AI literature in medicine, the following tools have been commonly used:

## Assessing reporting quality within studies:

### CONSORT-AI

> Provides a set of recommendations for clinical trials evaluating interventions with an AI component
<a target="_blank" href="https://www.clinical-trials.ai/consort" class="btn {{ f.btn_class }}">Link</a>

### CLAIM
> Provides a checklist for reporting of medical image studies which uses AI<a target="_blank" href="https://pubs.rsna.org/doi/10.1148/ryai.240300" class="btn {{ f.btn_class }}">Link</a>

### DECIDE-AI
> Reporting guideline for clinical evaluation of decision-support systems based on AI <a target="_blank" href="https://www.clinicalradiologyonline.net/article/S0009-9260(22)00704-8/fulltext" class="btn {{ f.btn_class }}">Link</a>	

### STARD-AI (in development) 
> An AI-centric guideline based on the original STARD 2015 guideline which was developed to improve the reporting quality of studies investigating diagnostic test accuracy <a target="_blank" href="https://bmjopen.bmj.com/content/11/6/e047709" class="btn {{ f.btn_class }}">Related Publication</a> <a target="_blank" href="https://www.equator-network.org/reporting-guidelines/stard" class="btn {{ f.btn_class }}">STARD 2015</a>

### SPIRIT-AI 
> Reporting guideline for clinical trial protocols evaluating interventions with an AI component <a target="_blank" href="https://www.equator-network.org/reporting-guidelines/spirit-artificial-intelligence/" class="btn {{ f.btn_class }}">Link</a>

### TRIPOD-AI
> Reporting guidance for clinical prediction model that uses regression or machine learning methods <a target="_blank" href="https://www.equator-network.org/reporting-guidelines/tripod-statement/" class="btn {{ f.btn_class }}">Link</a> <a target="_blank" href=" https://www.acpjournals.org/doi/10.7326/M14-0698" class="btn {{ f.btn_class }}">Original TRIPOD 2015</a>

### PRISMA-AI (in development) 
> A steering committee has been established to update PRISMA guidelines for applicability in AI literature <a target="_blank" href="https://www.nature.com/articles/s41591-022-02139-w" class="btn {{ f.btn_class }}">Related Publication</a> 

## Assessing for risk of bias within studies:

### QUADAS-AI (in development)
> Tool in development to assess risk of bias in primary diagnostic accuracy studies that have an AI component <a target="_blank" href="https://www.nature.com/articles/s41591-021-01517-0" class="btn {{ f.btn_class }}">Related Publication</a>

### QUADAS-2
> Used to assess risk of bias in primary diagnostic accuracy studies <a target="_blank" href="https://www.bristol.ac.uk/population-health-sciences/projects/quadas/quadas-2" class="btn {{ f.btn_class }}">Link</a>

### CHARMS
> Checklist to appraise all types of primary prediction modelling studies including regressions, neural networks, genetic programming and vector machine learning models <a target="_blank" href="https://journals.plos.org/plosmedicine/article?id=10.1371/journal.pmed.1001744" class="btn {{ f.btn_class }}">Link</a>

### PROBAST-AI (in development)
> A tool based on the original PROBAST tool to assess both quality of reporting and risk of bias on studies developing and evaluating multivariable diagnostic and prognostic prediction models using any AI/ML technique <a target="_blank" href="https://bmjopen.bmj.com/content/bmjopen/11/7/e048008.full.pdf" class="btn {{ f.btn_class }}">Related Publication</a>
<a target="_blank" href="https://www.acpjournals.org/doi/full/10.7326/M18-1376" class="btn {{ f.btn_class }}">Original PROBAST Tool</a>


## Successful Application of Tools
Though these tools are becoming more commonly used,, the high level of heterogeneity in primary AI literature and poor reporting practices can make it challenging to use. Examples of successful application of these tools can be found below:

> Systematic review of ML-based diagnostic imaging models using CLAIM & QUADAS-2
Lans A, Pierik RJB, Bales JR, Fourman MS, Shin D, Kanbier LN, Rifkin J, DiGiovanni WH, Chopra RR, Moeinzad R, Verlaan JJ, Schwab JH. Quality assessment of machine learning models for diagnostic imaging in orthopaedics: A systematic review. Artif Intell Med. 2022 Oct;132:102396. doi: 10.1016/j.artmed.2022.102396. Epub 2022 Sep 6. PMID: 36207080.

> Systematic review and meta-analysis of a comparison of deep learning performance against health-care professionals in detecting diseases from medical imaging using CHARMS Liu X, Faes L, Kale AU, Wagner SK, Fu DJ, Bruynseels A, Mahendiran T, Moraes G, Shamdas M, Kern C, Ledsam JR. A comparison of deep learning performance against health-care professionals in detecting diseases from medical imaging: a systematic review and meta-analysis. The lancet digital health. 2019 Oct 1;1(6):e271-97.

> Systematic review of claims of deep learning studies in medical imaging using TRIPOD, Cochrane risk of bias tool for RCTs, and PROBAST 
Nagendran M, Chen Y, Lovejoy CA, et al. Artificial intelligence versus clinicians: systematic review of design, reporting standards, and claims of deep learning studies. BMJ. 2020;368:m689.

## References
[^fn1]: Figure 1 taken from [here](https://commons.wikimedia.org/wiki/Category:Hierarchy_of_evidence#/media/File:Medical_guide.png)
[^fn2]: Nagendran M, Chen Y, Lovejoy CA, et al. Artificial intelligence versus clinicians: systematic review of design, reporting standards, and claims of deep learning studies. BMJ. 2020;368:m689.
