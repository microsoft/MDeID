
# MDeID: A Dataset for Multilingual Medical De-Identification

[![Paper](https://img.shields.io/badge/Status-Published-brightgreen)](https://www.sciencedirect.com/science/article/pii/S1532046426001309)
[![License](https://img.shields.io/badge/License-Research%20Only-lightgrey.svg)](license.md)

This repository contains the dataset for the paper:

**"MDeID: A Dataset for Multilingual Medical De-Identification"**
Risha Surana, Rodolfo Quispe, Alistair Johnson, Thomas Lin
Microsoft Corporation
Posted: January 29, 2026

📄 Paper available at: [[https://ssrn.com/abstract=6122896](https://ssrn.com/abstract=6122896](https://www.sciencedirect.com/science/article/pii/S1532046426001309))

---

## Overview

Medical Text De-identification (DeID) is essential for protecting Protected Health Information (PHI) and ensuring compliance with privacy regulations such as HIPAA. While numerous English benchmarks exist, multilingual de-identification datasets remain scarce.

**MDeID** introduces a large-scale, multilingual benchmark designed to evaluate and improve medical de-identification systems across multiple languages and clinical domains.

---

## Framework Overview

[MDeID Graphical Abstract (PDF)](graphical-abstract.pdf)

*Figure 1: Overview of the MDeID dataset spanning seven languages, seven medical domains, and 28 PHI categories.*

---

## Abstract

Medical Text De-identification (DeID) is a critical process in securing Protected Health Information (PHI) in compliance with regulations such as the Health Insurance Portability and Accountability Act (HIPAA). Multiple benchmark datasets exist for English, but there is a paucity of multilingual datasets. We introduce MDeID, an openly available and uniquely challenging multilingual medical dataset comprising 6,034 clinical notes. MDeID covers 28 PHI categories in seven languages: English, Spanish, Portuguese, French, Italian, Dutch, and German. MDeID encompasses seven distinct domains of medical notes for each language: discharge summaries, provider notes, diagnosis and health plans, nursing notes, emergency medical services notes, scratch notes, and Subjective, Objective, Assessment and Plan (SOAP) notes.

MDeID is synthetically generated, seeded with real-world data, and constructed by selectively upweighting difficult examples to provide a more challenging corpus. We analyze the behavior of models both trained and evaluated on MDeID and contrast it with experiments using real-world and translated datasets. Our work demonstrates MDeID is an effective benchmark and resource for improving the quality of DeID models.

---

## Dataset Summary

* 📄 **6,034 clinical notes**
* 🌍 **7 languages**: English, Spanish, Portuguese, French, Italian, Dutch, German
* 🏥 **7 clinical domains per language**
* 🔐 **28 PHI categories**
* 🧪 **Synthetic data seeded with real-world examples**

---

## Dataset Construction

MDeID is synthetically generated and seeded with real-world data. The dataset was curated to emphasize difficult de-identification scenarios by selectively upweighting challenging PHI instances, resulting in a more rigorous benchmark for evaluating modern NLP systems and large language models.

The dataset spans multiple clinical domains to ensure robustness across documentation styles and care settings.

---

## Repository Structure

```
MDeID/
├── data/
│   ├── english/
│   ├── spanish/
│   ├── portuguese/
│   ├── french/
│   ├── italian/
│   ├── dutch/
│   └── german/
├── graphical-abstract.png
└── README.md
```


---

## Intended Use

MDeID is intended for:

* Benchmarking multilingual DeID systems
* Training and evaluating medical NLP models
* Studying cross-lingual transfer for PHI detection
* Evaluating privacy robustness of large language models

This dataset is not intended for clinical deployment or direct medical decision-making.

---

## Funding

This work was funded by Microsoft Corporation.

---

## Declaration of Interests

All authors are affiliated with Microsoft Corporation.

---

## Citation

If you use MDeID in your research, please cite:

> Surana, Risha, Rodolfo Quispe, Alistair Johnson, and Thomas Lin.
> *MDeID: A dataset for multilingual medical de-identification.*
> Journal of Biomedical Informatics (2026).
> [https://doi.org/10.1016/j.jbi.2026.105106](https://doi.org/10.1016/j.jbi.2026.105106)

### BibTeX

```bibtex
@article{surana2026mdeid,
  title={{MDeID}: A dataset for multilingual medical de-identification},
  author={Surana, Risha and Quispe, Rodolfo and Johnson, Alistair and Lin, Thomas},
  journal={Journal of Biomedical Informatics},
  year={2026},
  doi={10.1016/j.jbi.2026.105106},
  url={https://doi.org/10.1016/j.jbi.2026.105106}
}
```
