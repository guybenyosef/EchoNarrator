# EchoNarrator: Generating Natural Text Explanations for Ejection Fraction Predictions (MICCAI 2024)

[Link to Paper](https://arxiv.org/abs/2410.23744)

## Introduction

Ejection fraction (EF) of the left ventricle (LV) is considered as one of the most important measurements for diagnosing acute heart failure and can be estimated during cardiac ultrasound acquisition. While recent successes in deep learning research successfully estimate EF values, the proposed models often lack an explanation for the prediction. However, providing clear and intuitive explanations for clinical measurement predictions would increase the trust of cardiologists in these models. In this paper, we explore predicting EF measurements with Natural Language Explanation (NLE). We propose a model that in a single forward pass combines estimation of the LV contour over multiple frames, together with a set of modules and routines for computing various motion and shape attributes that are associated with ejection fraction. It then feeds the attributes into a large language model to generate text that helps to explain the network's outcome in a human-like manner. We provide experimental evaluation of our explanatory output, as well as EF prediction, and show that our model can provide EF comparable to state-of-the-art together with meaningful and accurate natural language explanation to the prediction.


# Getting Started

Detailed setup instructions and documentation will be available soon. 


## License and Citation

A patent has been filed based on this technology. If you use this code in your research, please cite our paper:

```bibtex
@inproceedings{thomas2024echonarrator,
  title={EchoNarrator: Generating natural text explanations for ejection fraction predictions},
  author={Thomas, Sarina and Cao, Qing and Novikova, Anna and Kulikova, Daria and Ben-Yosef, Guy},
  booktitle={International Conference on Medical Image Computing and Computer-Assisted Intervention (MICCAI)},
  pages={634--644},
  year={2024},
  organization={Springer}
}
```

---

This repository is designed to support researchers and practitioners interested in explainable AI for cardiovascular imaging. Thank you for your interest, and we welcome your feedback and contributions!

