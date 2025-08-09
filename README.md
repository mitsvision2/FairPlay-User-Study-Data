# FairPlay Dataset: Consensus-Driven Data Debiasing for Hiring Decisions

This repository contains the **FairPlay User Study Dataset**, which has been made publicly available to support transparency and reproducibility in research. The dataset is a part of the FairPlay project, a tool designed for collaborative debiasing and fairness exploration in datasets.

## Contents

- `Fairplay.zip`: A compressed folder containing three subfolders, each corresponding to a user study. Each subfolder contains a separate CSV file for each FairPlay round.
  - **Userstudy 1**: User Study 1 with its corresponding CSV files for each round.
  - **Userstudy 2**: User Study 2 with its corresponding CSV files for each round.
  - **Userstudy 3**: User Study 3 with its corresponding CSV files for each round.
  
## Description

The dataset includes anonymized user study data used for analyzing collaborative fairness workflows. The data is structured to facilitate research and analysis for applications such as:
- Collaborative fairness evaluation.
- Stakeholder interactions in AI model development.

# Attribution

If you use this dataset in your research or projects, please cite the following papers and dataset:

## Main Journal Publication

```bibtex
@article{10.1145/3710982,
author = {Behzad, Tina and Singh, Mithilesh Kumar and Ripa, Anthony J. and Mueller, Klaus},
title = {FairPlay: A Collaborative Approach to Mitigate Bias in Datasets for Improved AI Fairness},
year = {2025},
issue_date = {May 2025},
publisher = {Association for Computing Machinery},
address = {New York, NY, USA},
volume = {9},
number = {2},
url = {https://doi.org/10.1145/3710982},
doi = {10.1145/3710982},
abstract = {The issue of fairness in decision-making is a critical one, especially given the variety of stakeholder demands for differing and mutually incompatible versions of fairness. Adopting a strategic interaction of perspectives provides an alternative to enforcing a singular standard of fairness. We present a web-based software application, FairPlay, that enables multiple stakeholders to debias datasets collaboratively. With FairPlay, users can negotiate and arrive at a mutually acceptable outcome without a universally agreed-upon theory of fairness. In the absence of such a tool, reaching a consensus would be highly challenging due to the lack of a systematic negotiation process and the inability to modify and observe changes. We have conducted user studies that demonstrate the success of FairPlay, as users could reach a consensus within about five rounds of gameplay, illustrating the application's potential for enhancing fairness in AI systems.},
journal = {Proc. ACM Hum.-Comput. Interact.},
month = may,
articleno = {CSCW084},
numpages = {30},
keywords = {bias, causal networks, datasets, fairness}
}
```

---

## Workshop Paper

```bibtex
@inproceedings{
behzad2024fairplay,
title={FairPlay: A Collaborative Approach to Mitigate Bias in Datasets for Improved {AI} Fairness},
author={Tina Behzad and Mithilesh Kumar Singh and Anthony J. Ripa and Klaus Mueller},
booktitle={Pluralistic Alignment Workshop at NeurIPS 2024},
year={2024},
url={https://openreview.net/forum?id=7StJj749GW}
}
```

---

## Dataset Citation

```bibtex
@misc{data_fairplay,
author = {Behzad, Tina and Singh, Mithilesh Kumar and Ripa, Anthony J. and Mueller, Klaus},
title = {FairPlay Dataset: Consensus-Driven Data Debiasing for Hiring Decisions},
year = {2024},
howpublished = {\url{https://github.com/mitsvision2/FairPlay-User-Study-Data}},
note = {Accessed: 2024-12-18}
}
```
