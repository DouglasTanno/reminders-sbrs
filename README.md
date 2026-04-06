# Reminders in Session-Based Recommender Systems

This repository contains the preprocessed dataset slices and citations of the original datasets and the framework used in the experiments reported in our work.  

## Datasets

The original datasets are **not included**, as they are owned by third parties. References to the original sources are provided below, and users should obtain the datasets from these sources:  

- **JusBrasilRec** – Domingues et al., 2023 [Link](https://link.springer.com/article/10.1007/s10506-023-09378-3)  
- **Xing** – Abel et al., 2016 [Link](https://dl.acm.org/doi/10.1145/2959100.2959196)  
- **Music4All** – Pegoraro Santana et al., 2020 [Link](https://ieeexplore.ieee.org/document/9094737)  
- **RetailRocket** – Zykov, 2022 [Link](https://www.kaggle.com/datasets/retailrocket/ecommerce-dataset)  
- **MIND** – Wu et al., 2020 [Link](https://doi.org/10.18653/v1/2020.acl-main.331)  
- **Trivago** – Knees et al., 2019 [Link](https://dl.acm.org/doi/10.1145/3298689.3347008)  

The preprocessed slices included here are derived from these datasets and reflect the subsets actually used in our experiments, including session filtering and item selection steps.

## Code

The experiments were conducted using the **[session-rec](https://github.com/rn5l/session-rec)** framework. This repository **does not include the framework itself**, so please follow the instructions in the official repository to set up the environment.

## Citation

If you use these preprocessed slices in your work, please cite our paper:

**anonymized**

## References

- Domingues, M. A., de Moura, E. S., Marinho, L. B., & da Silva, A. (2023). 
  *A large scale benchmark for session-based recommendations on the legal domain*. Artificial Intelligence and Law, 1–36. [Link](https://link.springer.com/article/10.1007/s10506-023-09378-3)

- Abel, F., Benczúr, A., Kohlsdorf, D., Larson, M., & Pálovics, R. (2016). 
  *RecSys challenge 2016: Job recommendations*. Proceedings of the 10th ACM Conference on Recommender Systems, 425–426. [Link](https://dl.acm.org/doi/10.1145/2959100.2959196)

- Pegoraro Santana, I. A., Pinhelli, F., Donini, J., Catharin, L., Mangolin, R. B., da Costa, Y. M. e Gomes, & Delisandra, V., Domingues, M. A. (2020). 
  *Music4All: A New Music Database and Its Applications*. 2020 International Conference on Systems, Signals and Image Processing (IWSSIP), 399–404. [Link](https://ieeexplore.ieee.org/document/9094737)

- Knees, P., Deldjoo, Y., Moghaddam, F. B., Adamczak, J., Leyson, G.-P., & Monreal, P. (2019). 
  *RecSys challenge 2019: Session-based hotel recommendations*. Proceedings of the 13th ACM Conference on Recommender Systems, 570–571. [Link](https://dl.acm.org/doi/10.1145/3298689.3347008)

- Wu, F., Qiao, Y., Chen, J.-H., Wu, C., Qi, T., Lian, J., Liu, D., Xie, X., Gao, J., Wu, W., & Zhou, M. (2020). 
  *MIND: A Large-scale Dataset for News Recommendation*. Proceedings of the 58th Annual Meeting of the Association for Computational Linguistics, 3597–3606. [DOI:10.18653/v1/2020.acl-main.331](https://doi.org/10.18653/v1/2020.acl-main.331)

- Zykov, R. (2022). *Retailrocket Recommender System Dataset*. Available on [Kaggle](https://www.kaggle.com/datasets/retailrocket/ecommerce-dataset). Accessed: 2025-05-01.
