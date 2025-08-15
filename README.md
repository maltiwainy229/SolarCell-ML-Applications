# SolarCell-ML-Applications
Applying machine learning to analyze solar cell performance and predict efficiency.

<img width="475" height="475" alt="Image" src="https://github.com/user-attachments/assets/3ed1b604-52a5-4bee-a516-e6899c3b2656" />

## Overview

This repository contains Jupyter notebooks, environment specifications, and data used to explore and model solar cell performance using machine learning methods. The goals are:
- Reproduce experiments and analyses.
- Provide notebooks that walk through data ingestion, feature engineering, model training, and evaluation.
- Offer reusable environment files to reproduce results.

## Getting started

1. Clone the repo:
```bash
git clone https://github.com/maltiwainy229/SolarCell-ML-Applications.git
cd SolarCell-ML-Applications
```

## Data

See [`data`](data) for data sources. 

## Notebooks
[`notebooks`](notebooks) - each notebook contains markdown descriptions and explanations, see in-file comments and docstrings for more details in source scripts. Run the notebooks top-to-bottom to reproduce results.

## Model File
Due to GitHub size limits, the full [`pickle`](pickle) file (~100 GB) is hosted externally:
[Download from Google Drive](https://drive.google.com/file/d/1PpUy9nkPIpzvdHHDD-el9eJ5A4c_8k4o/view?usp=drive_link)

## Contributing

Contributions are welcome! 

If you plan to contribute code or updated notebooks:
- Create a feature branch from `main`.
- Keep notebooks reproducible: clear output cells before committing or use `nbstripout`.
- Run notebooks end-to-end before opening a PR.

## Credits & Resources

This project builds on and references the following repositories and resources:
- alvarovm/solarcelldata — https://github.com/alvarovm/solarcelldata
- edbeard/chemdataextractor-uvvis2018 — https://github.com/edbeard/chemdataextractor-uvvis2018
