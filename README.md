# Clothing1M_FedAvg
We open-source this Jupyter notebook to provide a simple and easy-to-understand code for related communities to conduct experiments on real-world noisy dataset `Clothing1M`, which can be helpful for researchers focusing on `robust distributed optimization` and `federated learning on noisy labels`.

# Usage
Simply run this notebook. We've previously tested this file on one Nvidia 3090 GPU with `Pytorch 3.8` version as the computation backend. There're not many related dependency requirements. We provide the FedAvg as the baseline method while you can add more optimization methods based on our code.

# Dataset
`Clothing1M` contains 1M clothing images in 14 classes. It is a dataset with noisy labels, since the data is collected from several online shopping websites and include many mislabelled samples. This dataset also contains 50k, 14k, and 10k images with clean labels for training, validation, and testing, respectively.

Please kindly refer to [this link](https://paperswithcode.com/dataset/clothing1m) to know about this dataset. Please contact `tong.xiao.work[at]gmail[dot]com` to get the download link. 

![clothing1m](https://production-media.paperswithcode.com/datasets/Clothing1M-0000000432-132e8198_olXM2iD.jpg)

# Recommended Literature
Here we provide some personal recommended papers, which can be helpful to whom have interests in `federated learning with noisy labels` or `federated noisy label learning (FNLL)`. 

| Method | Venue | Paper | Code | Team |
|--------|-------|-------|------|------|
|Robust FL| IEEE Intelligent System |[link](https://ieeexplore.ieee.org/abstract/document/9713942)|[link](https://github.com/jangsoohyuk/Robust-Federated-Learning-with-Noisy-Labels)| KAIST (Korea) | 
| FedLSR | ACM CIKM'22 | [link](https://dl.acm.org/doi/abs/10.1145/3511808.3557475)| [link](https://github.com/Sprinter1999/FedLSR)| ICT,CAS (China) |
| FedRN | ACM CIKM'22 | [link](https://dl.acm.org/doi/abs/10.1145/3511808.3557322)| [link](https://github.com/ElvinKim/FedRN)| KAIST (Korea) |
| RHFL | CVPR'22 & IEEE TMC | [link](https://openaccess.thecvf.com/content/CVPR2022/html/Fang_Robust_Federated_Learning_With_Noisy_and_Heterogeneous_Clients_CVPR_2022_paper.html)| [link](https://github.com/FangXiuwen/Robust_FL)| WHU (China) |
| FedNoRo | IJCAI'23 | [link](https://arxiv.org/abs/2305.05230)| [link](https://github.com/wnn2000/FedNoRo)| HUST (China) |
| FedNoisy | Under review | [link](https://arxiv.org/abs/2306.11650)| [link](https://github.com/SMILELab-FL/FedNoisy)| MSU (USA) |
| FNBench | Submitted to IEEE TDSC | [link](https://www.techrxiv.org/doi/full/10.36227/techrxiv.172503083.36644691)| TBD | ICT,CAS (China) |
| FedA3I | AAAI'24 | [link](https://ojs.aaai.org/index.php/AAAI/article/view/29525)| [link](https://github.com/wnn2000/FedAAAI)| HUST (China) |
| FedNed | AAAI'24 | [link](https://arxiv.org/abs/2312.12703)| [link](https://github.com/linChen99/FedNed)| XMU (China) |
| FedELC | ACM CIKM'24 | [link](https://arxiv.org/abs/2408.04301)| [link](https://github.com/Sprinter1999/FedELC)| ICT,CAS (China) |
| Dual Optim | Submitted to IEEE TIFS | [link](https://www.techrxiv.org/doi/full/10.36227/techrxiv.172503083.36644691)| [link](https://github.com/18sym/DualOptim) | ICT,CAS (China) |
|FLR|TMLR|[link](https://arxiv.org/abs/2402.05353)|TBD| KAIST (Korea) |


# Citing this work
Collaboration and Pull-requests are always welcomed. If you find this code helpful, please consider citing these works : )

```
@article{jiang2024tackling,
  title={Tackling Noisy Clients in Federated Learning with End-to-end Label Correction},
  author={Jiang, Xuefeng and Sun, Sheng and Li, Jia and Xue, Jingjing and Li, Runhan and Wu, Zhiyuan and Xu, Gang and Wang, Yuwei and Liu, Min},
  journal={arXiv preprint arXiv:2408.04301},
  year={2024}
}

@article{Jiang_2024,
title={FNBench: Benchmarking Robust Federated Learning against Noisy Labels},
url={http://dx.doi.org/10.36227/techrxiv.172503083.36644691/v1},
DOI={10.36227/techrxiv.172503083.36644691/v1},
publisher={Institute of Electrical and Electronics Engineers (IEEE)},
author={Jiang, Xuefeng and Li, Jia and Wu, Nannan and Wu, Zhiyuan and Li, Xujing and Sun, Sheng and Xu, Gang and Wang, Yuwei and Li, Qi and Liu, Min},
year={2024},
}

@inproceedings{xiao2015learning,
  title={Learning from Massive Noisy Labeled Data for Image Classification},
  author={Xiao, Tong and Xia, Tian and Yang, Yi and Huang, Chang and Wang, Xiaogang},
  booktitle={CVPR},
  year={2015}
}

@article{jiang2025refining,
  title={Refining Distributed Noisy Clients: An End-to-end Dual Optimization Framework},
  author={Jiang, Xuefeng and Li, Peng and Sun, Sheng and Li, Jia and Wu, Lvhua and Wang, Yuwei and Lu, Xiuhua and Ma, Xu and Liu, Min}
}

@inproceedings{wu2023fednoro,
  title={FedNoRo: towards noise-robust federated learning by addressing class imbalance and label noise heterogeneity},
  author={Wu, Nannan and Yu, Li and Jiang, Xuefeng and Cheng, Kwang-Ting and Yan, Zengqiang},
  booktitle={Proceedings of the Thirty-Second International Joint Conference on Artificial Intelligence},
  pages={4424--4432},
  year={2023}
}

@inproceedings{jiang2022towards,
  title={Towards federated learning against noisy labels via local self-regularization},
  author={Jiang, Xuefeng and Sun, Sheng and Wang, Yuwei and Liu, Min},
  booktitle={Proceedings of the 31st ACM International Conference on Information \& Knowledge Management},
  pages={862--873},
  year={2022
```
