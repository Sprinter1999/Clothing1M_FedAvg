# Clothing1M_FedAvg
We open-source this Jupyter notebook to provide a simple and easy-to-understand code for related communities, which can be helpful for researchers focusing on `robust distributed optimization` and `federated learning on noisy labels`.

# Usage
Simply run this notebook. We've previously tested this file on one Nvidia 3090 GPU with Pytorch 3.8 version as the computation backend. There're not many related dependency requirements. We provide the FedAvg as the baseline method while you can add more optimization methods based on our code.

# Dataset
Please kindly refer to [this link](https://paperswithcode.com/dataset/clothing1m) to know about this dataset. Please contact `tong.xiao.work[at]gmail[dot]com` to get the download link. 

# Recommended Literature
TBD

# Citing this work
If you find this code helpful, please consider citing these works : )
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
