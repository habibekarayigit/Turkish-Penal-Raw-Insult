# TPL-I: Turkish Penal Law – Insult Dataset

## Overview

TPL-I (Turkish Penal Law – Insult) is a dataset of **7,361 Turkish-language
Instagram comments** annotated for **legally defined insult detection**.
Unlike general offensive-language or toxicity datasets, the labels follow
the legal criteria of **Articles 125–131 of the Turkish Penal Code (TPL)**.
Not every rude or offensive comment constitutes a legally sanctionable
insult; TPL-I was built specifically to capture this legal distinction.

## Dataset Details

| Property | Value |
|---|---|
| Language | Turkish |
| Source | Instagram comments sent to the accounts of a popular women's program broadcast on weekdays in Turkey |
| Collection period | 2024 |
| Total instances | 7,361 |
| Class 1 (legally defined insult) | 3,652 |
| Class 0 (non-insult) | 3,709 |
| Annotation | Manual labeling by domain-expert annotators |
| Inter-annotator agreement | Cohen's kappa = 0.940 |

## Labeling Criteria

A comment is labeled **1 (insult)** if, according to TPL Articles 125–131,
it may constitute a criminal insult — for example, a direct attack on the
honor, dignity, or reputation of a specific or identifiable person,
including animal-name comparisons recognized as insults by the Court of
Cassation. A comment is labeled **0 (non-insult)** if it does not exceed
the legal threshold, such as curses, imprecations, harsh institutional or
political criticism, untargeted emotional outbursts, or rude remarks that
do not target a person's dignity.

## How to Obtain the Dataset

The dataset file is **not distributed through this repository**. To obtain
TPL-I, please send an access request by e-mail to:

**habibekarayigit@aof.anadolu.edu.tr**

Please use the subject line: **"TPL-I Dataset Access Request"**

Your request should include:

1. Your full name
2. Your institution and department
3. Your institutional e-mail address
4. A short description of your research purpose and intended use of the dataset

The dataset is shared **only for non-commercial academic research
purposes**. Requests are typically answered within a few working days.

## Citation

If you use this dataset, please cite the original publication:

> Karayiğit H. Leveraging attention-based deep learning models for detecting
> insult offenses on social media in the context of Turkish Penal Law.
> *Neural Computing and Applications*, 38(1), 2026.
> https://doi.org/10.1007/s00521-025-11807-0

## Terms of Use

By receiving the dataset, you agree **not** to:

- redistribute, resell, or publicly re-publish the dataset;
- attempt to identify, contact, or profile the original comment authors;
- use the dataset for any commercial or non-academic purpose.

The dataset compilation, structure, and annotations are provided by the
author for academic use. The underlying comments were written by
third-party social-media users; no rights in the comment texts themselves
are transferred.

## Contact

Habibe Karayiğit
General Directorate of Secondary Education, Ministry of National Education, Adana, Türkiye
**habibekarayigit@aof.anadolu.edu.tr**
