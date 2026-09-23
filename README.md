# DASS — Density-Adaptive Synthetic Sampling

Reference repository for the conference paper **“DASS: Density-Adaptive Synthetic
Sampling for Improved Imbalanced Classification.”**

📄 **Paper:** [IEEE Xplore · 10.1109/STI64222.2024.10951098](https://doi.org/10.1109/STI64222.2024.10951098)

## What the paper is about

When one class in a dataset vastly outnumbers another, a classifier can score well
simply by ignoring the rare class — which is usually the class that matters. The
standard answer is to synthesise extra minority-class examples, and the usual
methods for doing so (ADASYN, RSMOTE) place those synthetic points without much
regard for where the minority data actually sits, so outliers and regions where the
classes overlap end up amplified.

DASS chooses the neighbours it interpolates between using a local density estimate,
so synthetic points are drawn from where the minority class genuinely is rather than
from its sparse edges. The paper reports that this reduces overfitting and
generalises better than the baselines it was compared against.

The full abstract, experimental setup and results are in the paper linked above.

## Citing this work

```bibtex
@inproceedings{almuzahid2024dass,
  author    = {Al-Muzahid, Muhammad and Masud, Md Abdul and Samsuzzaman, Md. and Islam, Md. Jahidul},
  title     = {{DASS}: Density-Adaptive Synthetic Sampling for Improved Imbalanced Classification},
  booktitle = {2024 6th International Conference on Sustainable Technologies for Industry 5.0 (STI)},
  year      = {2024},
  pages     = {1--6},
  publisher = {IEEE},
  address   = {Dhaka, Bangladesh},
  doi       = {10.1109/STI64222.2024.10951098},
  isbn      = {979-8-3315-3197-3}
}
```

A `CITATION.cff` file is included, so GitHub's **“Cite this repository”** button
offers the same reference in APA and BibTeX.

## Publication details

| | |
|---|---|
| Conference | 2024 6th International Conference on Sustainable Technologies for Industry 5.0 (STI) |
| Host | Green University of Bangladesh, 14–15 December 2024 |
| Publisher | IEEE · added to IEEE Xplore 14 December 2024 |
| DOI | [10.1109/STI64222.2024.10951098](https://doi.org/10.1109/STI64222.2024.10951098) |
| Pages | 1–6 |
| ISBN | 979-8-3315-3197-3 |

## Authors

Muhammad Al-Muzahid · Md Abdul Masud · Md. Samsuzzaman · Md. Jahidul Islam

## Status of the code

This repository does not yet contain the DASS implementation — it currently serves
as the citable landing page for the paper. The MIT licence below applies to whatever
source is published here; the paper itself remains © IEEE.

## Licence

[MIT](LICENSE) for the code in this repository.
