## HeST

This is a Pytorch implementation of the <u>He</u>terogeneity-aware <u>S</u>patial <u>T</u>emporal (HeST) framework for traffic flow prediction in a self-supervised learning fashion.

### Requirement

We build this project by Python 3.8 with the following packages: 
```
numpy==1.21.2
pandas==1.3.5
PyYAML==6.0
torch==1.10.1
```

### Model training and Evaluation

If the environment is ready, please run the following commands to train model on the specific dataset from `{NYCBike1, NYCBike2, NYCTaxi, BJTaxi}`.
```bash
>> cd HeST
>> ./runme 0 NYCBike1   # 0 gives the gpu id
```
