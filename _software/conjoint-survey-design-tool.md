---
title: "Conjoint Survey Design Tool"
collection: software
order: 3
excerpt: "A graphical tool for designing conjoint experiments and exporting them to web survey platforms such as Qualtrics, with randomization handled entirely within the survey."
language: Python
availability: Windows binary or Python source
links:
  - label: 'github'
    url: 'https://github.com/astrezhnev/conjointsdt'
related:
  - title: 'Hainmueller, Hopkins and Yamamoto (2014). "Causal Inference in Conjoint Analysis: Understanding Multidimensional Choices via Stated Preference Experiments." Political Analysis 22(1): 1-30.'
    url: 'https://doi.org/10.1093/pan/mpt024'
---

## Installation

Windows users can download and run the standalone `conjointSDT.exe` from the repository. On macOS and Linux, run the source with Python 3.6 or later:

```bash
python3 conjointSDT.py
```

The repository includes a user manual and a sample survey file. Version 3.0 added a JavaScript randomizer that runs inside a Qualtrics question, so no separate server is needed. Completed designs can be analyzed with the [cjoint](/software/cjoint/) R package.
