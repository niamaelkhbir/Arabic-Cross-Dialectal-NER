# Arabic Cross-Dialectal Named Entity Recognition

## Overview

This project explores the transferability of Named Entity Recognition (NER) models between Arabic dialects. The primary focus is on datasets, annotation guidelines, and experimental results. For the code and model training, please visit [Filtered-Semi-Markov-CRF](https://github.com/urchade/Filtered-Semi-Markov-CRF).

## Installation & Usage

To install the required dependencies and use the project, please follow the guidelines provided in [Filtered-Semi-Markov-CRF](https://github.com/urchade/Filtered-Semi-Markov-CRF). For the configuration options, please use:

    model_type: "standard"
    decoding: "global"


## Dataset and Annotation

The project uses datasets from the ACE 2005 corpus for Modern Standard Arabic (MSA) and the xP3x corpus for Arabic dialects (Moroccan, Egyptian, Syrian). The annotation guidelines are provided based on the ACE guidelines.

## Citation

If you find this code useful in your research, please consider citing our papers:

```bibtex
@inproceedings{elkhbir-etal-2023-cross,
    title = "Cross-Dialectal Named Entity Recognition in {A}rabic",
    author = "Elkhbir, Niama  and
      Zaratiana, Urchade  and
      Tomeh, Nadi  and
      Charnois, Thierry",
    booktitle = "Proceedings of ArabicNLP 2023",
    month = dec,
    year = "2023",
    address = "Singapore (Hybrid)",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2023.arabicnlp-1.12",
    doi = "10.18653/v1/2023.arabicnlp-1.12",
    pages = "140--149",
}
