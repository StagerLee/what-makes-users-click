# What Makes a User Click on a News Item?
Understanding News Values of Visual Content in News Recommendation (TPDL 2025)

## Reference
Sotic, B.N., & Kamps, J. (2025). *What Makes a User Click on a News Item? Understanding News Values of Visual Content in News Recommendation*. In *Proceedings of the International Conference on Theory and Practice of Digital Libraries (TPDL 2025)*.

## Overview
This repository contains the resources introduced in the TPDL 2025 findings paper.  
We extend the Microsoft News Dataset (MIND) with lead images and human annotations of **News Value Theory (NVT) factors**, creating the first large scale resource for analyzing how visual features relate to click behavior in news recommendation.

## Data Description
- **Original Dataset**: The Microsoft News Dataset (MIND), available at [msnews.github.io](https://msnews.github.io/) - needed for engagement metrics. 
- **Images**: 15,080 crawled news thumbnails from MIND articles: https://amsuni-my.sharepoint.com/:f:/g/personal/b_nadalicsotic4_uva_nl/EgXqVe1HcJdLgItX1cb-4boBVUv4G7JGiuzd-0OJnB1q7w?e=XySZAK
- **Annotations**: 1,054 images annotated by three coders for the presence of News Value Factors as well as code and data on machine annotations (GPT4): https://amsuni-my.sharepoint.com/:f:/g/personal/b_nadalicsotic4_uva_nl/EtaVzzos7WdKtzHcx76LgeABVS4FZnWeqQwPvDafpS-Jmg?e=F7BcZD
- **Vision API Extracts**: Textual descriptions / tags of each image using Google Vision API: https://amsuni-my.sharepoint.com/:f:/g/personal/b_nadalicsotic4_uva_nl/EjjszlKfpZ1Jm2rXrGYLt28BA-BvydEi9eifuwpqeBz2WA?e=zHftek

⚠️ **Important**: The IDs of items (filenames of images and annotation entries) correspond directly to the original **MIND news IDs** (will add .py file with the names of the images for convenient filtering). 



## Citation
If you use this dataset or code, please cite:

```bibtex
@inproceedings{sotic2025mindnvt,
  author    = {Bruno N. Sotic and Jaap Kamps},
  title     = {What Makes a User Click on a News Item? Understanding News Values of Visual Content in News Recommendation},
  booktitle = {Proceedings of the International Conference on Theory and Practice of Digital Libraries (TPDL)},
  year      = {2025}
}
