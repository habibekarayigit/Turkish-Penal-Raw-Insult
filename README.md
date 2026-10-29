# TPL-I: Turkish Penal Law–Insult Dataset

## Overview

TPL-I (Turkish Penal Law–Insult) contains **7,361 Turkish-language Instagram
comments** annotated for legally defined insult detection. Unlike general
offensive-language or toxicity datasets, its labels follow the legal criteria
in Articles 125–131 of the Turkish Penal Code (TPC). TPL-I was developed to
distinguish legally relevant insults from rude, offensive, or critical
expressions that do not necessarily meet the applicable legal threshold.

## Dataset Details

| Property | Value |
|---|---|
| Language | Turkish |
| Source | Instagram comments posted to the accounts of a popular women’s television program broadcast on weekdays in Türkiye |
| Collection period | 2024 |
| Total instances | 7,361 |
| Class 1 (legally defined insult) | 3,652 |
| Class 0 (non-insult) | 3,709 |
| Annotation | Manual labeling by domain-expert annotators |
| Inter-annotator agreement | Cohen’s kappa = 0.940 |

## Labeling Criteria

A comment is labeled **1 (insult)** if it may constitute a legally defined
insult under Articles 125–131 of the Turkish Penal Code, such as a direct
attack on the honor, dignity, or reputation of a specific or identifiable
person.

A comment is labeled **0 (non-insult)** if it does not meet the relevant legal
threshold, such as an imprecation, harsh institutional or political criticism,
an untargeted emotional outburst, or a rude expression that does not directly
attack an identifiable person’s dignity.

## Reviewer-Only Controlled Access

An encrypted copy of the TPL-I dataset is hosted in this repository solely to
facilitate confidential journal peer review. The file may be visible and
downloadable, but its contents cannot be opened without a password.

The password is provided only to authorized journal editors and reviewers.
Therefore, this repository does not provide public access to the readable
contents of the dataset.

To the best of the authors’ knowledge, TPL-I has been used only in the original
dataset study and the present work.

## Citation

Please cite the following publication when referring to TPL-I:

> Karayiğit H. Leveraging attention-based deep learning models for detecting
> insult offenses on social media in the context of Turkish Penal Law.
> *Neural Computing and Applications*. 2026;38(1):6.
> https://doi.org/10.1007/s00521-025-11807-0

## Terms of Use

Access to the readable dataset is restricted to authorized journal editors and
reviewers during the confidential peer-review process. The dataset must not be:

- redistributed, resold, or publicly republished;
- used outside the authorized peer-review process without permission;
- used to identify, contact, or profile the original comment authors;
- used for commercial or non-academic purposes.

The dataset compilation, structure, and annotations were prepared for academic
research. The underlying comments were written by third-party social-media
users; no rights in the original comment texts are transferred.

## Contact

**Habibe Karayiğit**  
General Directorate of Secondary Education  
Ministry of National Education  
Adana, Türkiye  
habibekarayigit@aof.anadolu.edu.tr
