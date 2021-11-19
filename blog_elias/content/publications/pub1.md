---
title: "Robust and Decomposable Average Precision for Image Retrieval"
thumbnail: images/outline.png
authors:
- Elias Ramzi
- Nicolas Thome
- Clément Rambour
- Nicolas Audebert
- Xavier Bitot
date: "2021-12-06"

publication: "Thirty-Fifth Conference on Neural Information Processing Systems"

abstract: "In image retrieval, standard evaluation metrics rely on score ranking, e.g. average precision (AP). In this paper, we introduce a method for robust and decomposable average precision (ROADMAP) addressing two major challenges for end-to-end training of deep neural networks with AP: non-differentiability and non-decomposability.
Firstly, we propose a new differentiable approximation of the rank function, which provides an upper bound of the AP loss and ensures robust training. Secondly, we design a simple yet effective loss function to reduce the decomposability gap between the AP in the whole training set and its averaged batch approximation, for which we provide theoretical guarantees.
Extensive experiments conducted on three image retrieval datasets show that ROADMAP outperforms several recent AP approximation methods and highlight the importance of our two contributions. Finally, using ROADMAP for training deep models yields very good performances, outperforming state-of-the-art results on the three datasets.
Code and instructions to reproduce our results will be made publicly available at https://github.com/elias-ramzi/ROADMAP."

bibtex: "@inproceedings{
ramzi2021robust,
title={Robust and Decomposable Average Precision for Image Retrieval},
author={Elias Ramzi and Nicolas THOME and Cl{\'e}ment Rambour and Nicolas Audebert and Xavier Bitot},
booktitle={Thirty-Fifth Conference on Neural Information Processing Systems},
year={2021},
url={https://openreview.net/forum?id=VjQw3v3FpJx}
}"

links:
    pdf: https://arxiv.org/abs/2110.01445
    code: https://github.com/elias-ramzi/ROADMAP
    #slides: https://github.com/hadisinaee/avicenna
    #video: https://github.com/hadisinaee/avicenna
---
