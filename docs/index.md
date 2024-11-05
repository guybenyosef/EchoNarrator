---
layout: default
---

# Abstract

#### Motivation
The EchoNarrator project aims to bridge the gap between automated EF prediction and clinician interpretability. By providing natural language explanations for echocardiography insights, EchoNarrator enhances trust and transparency, supporting clinicians in making informed decisions.

#### Summary 
EchoNarrator combines a Graph Convolutional Network (GCN) for EF prediction with a Large Language Model (LLM) to generate human-readable explanations. This integration produces accurate EF estimates alongside clear, text-based explanations for better clinical understanding of model predcitions.

#### Results
Our model achieves robust EF predictions with high accuracy and clinically relevant natural language explanations. Evaluations demonstrate improved interpretability and alignment with clinical expectations, highlighting EchoNarrator’s potential for real-world applications.

## Article

The paper is accepted for publication in the 2024 International Conference on Medical Image Computing and Computer 
Assisted Intervention. 

If you find the work interesting, please cite it:

Citation: 

S. Thomas, Q. Cao, Daria K., Anna N., and G. Ben-Yosef, “Generating natural text explanations for ejection fraction predictions”,
International Conference on Medical Image Computing and Computer-Assisted Intervention (MICCAI). Springer, Cham, 2024.


[//]: # (## Supplementary Materials)
[//]: # (Appendices referenced in the article are [available here]&#40;TBD&#41;)

# Data

The paper relied on the EchoNet dataset which is [available from Stanford here](https://echonet.github.io/dynamic/index.html). 
We would like to thank the authors [(Ouyang et. al, 2020)](https://www.nature.com/articles/s41586-020-2145-8) for making these 
resources available. 



# Code

The code is available [on GitHub](https://github.com/guybenyosef/EchoNarrator)


## Authors

Authors: Sarina Thomas<sup>1</sup>, Qing Cao <sup>2</sup>, Daria Kulikova<sup>2</sup>,
Anna Novikova<sup>2</sup> and Guy Ben-Yosef<sup>4,*</sup>


1: University of Oslo, Oslo, NO

2: GE Healthcare Ultrasound, Wuxi, China

3: GE Healthcare, Kharxiv, Ukraine

4: GE HealthCare Technology and Innovation Center, Niskayuna, New York, USA

*: Corresponding author: guy.ben-yosef@gehealthcare.com
