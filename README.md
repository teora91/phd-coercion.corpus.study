# Norwegian Aspectual Verbs Sentence Extractor 1.0

## Description
This project provides scripts and tools for extracting sentences containing aspectual verbs in Norwegian from the Norwegian Colossal Corpus (NCC).

> **Note:** Extracted sentences may include non-verbs, as the extractor matches strings with similar patterns to aspectual verbs. This method is employed to handle the vast size of the corpus, drastically reducing the sample size while preserving meaningful matches.

## Features
- **Efficient Pattern Matching:** Extracts sentences matching strings related to aspectual verbs. The list of aspectual verbs is found in __list_aspectual_verbs_nor.csv__
- **User-Friendly Outputs:** Extracted results saved in single CSV files for each sentence, preventing the generation of huge unmanageable files.

## Acknowledgements
- Special thanks to: 
	- NTNU for permitting the accomplishment of this project. 
	- Prof. Giosuè Baggio (NTNU) for his collaboration and suggestions.

## Contact Information
For questions or support, contact: 
- Email: matteo.radaelli91@gmail.com

## Badges
![Build Status](https://img.shields.io/badge/build-passing-brightgreen) ![Python Version](https://img.shields.io/badge/python-3.10%2B-blue)
