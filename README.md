# HeST (a.k.a ST-SSL)

This is a Pytorch implementation of the <u>He</u>terogeneity-aware <u>S</u>patial <u>T</u>emporal (HeST) framework in the following paper:

* J. Ji, J. Wang, C. Huang, et al. "Spatio-Temporal Self-Supervised Learning for Traffic Flow Prediction". in Thirty-Seventh AAAI Conference on Artificial Intelligence, 2023. 

Please visit the newer version at [ST-SSL](https://github.com/Echo-Ji/ST-SSL) repo.

## Requirement

We build this project by Python 3.8 with the following packages: 
```
numpy==1.21.2
pandas==1.3.5
PyYAML==6.0
torch==1.10.1
```

## Model training and Evaluation

If the environment is ready, please run the following commands to train model on the specific dataset from `{NYCBike1, NYCBike2, NYCTaxi, BJTaxi}`.
```bash
>> cd HeST
>> ./runme 0 NYCBike1   # 0 gives the gpu id
```

This repo contains the NYCBike1 data. If you are interested in other datasets, please download from [ST-SSL_Dataset](https://github.com/Echo-Ji/ST-SSL_Dataset).

<!-- ## Cite

If you find the paper useful, please cite as following:

```
@inproceedings{ji2023model, 
  title={Modeling Spatio-Temporal Heterogeneity for Traffic Flow Prediction via Self-Supervised Learning}, 
  author={Ji, Jiahao and Wang, Jingyuan and Huang, Chao and Wu, Junjie and Xu, Boren and Wu, Zhenhe and Zhang, Junbo and Zheng, Yu}, 
  booktitle={Proceedings of the AAAI Conference on Artificial Intelligence}, 
  year={2023}
}
``` -->
