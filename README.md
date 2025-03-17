# LLL-AFCA
This is a code demo for the paper "Lifelong Learning With Adaptive Knowledge Fusion and Class Margin Dynamic Adjustment for Hyperspectral Image Classification". IEEE Transactions on Geoscience and Remote Sensing, doi: 10.1109/TGRS.2025.3543406.
Zihui Jiang, Zhaokui Li*, Yan Wang, Wei Li, Ke Wang, Jing Tian, Chuanyun Wang, and Qian Du, "Lifelong Learning With Adaptive Knowledge Fusion and Class Margin Dynamic Adjustment for Hyperspectral Image Classification," IEEE Transactions on Geoscience and Remote Sensing, doi: 10.1109/TGRS.2025.3543406.

## Requirements

- CUDA = 10.2

- python = 3.7.11

- torch =1.9.1

- torchmetrics = 0.10.3

- scikit-learn  = 1.0.2

- numpy = 1.21.6

## Datasets

-  datasets
  - Houston13
  - Houston18
  - PaviaU
  - Salinas

You can download the source and target datasets mentioned above at https://pan.baidu.com/s/1LGzXX6iH1qGav0-xzIs0xw?pwd=67bk  Extraction code: 67bk, and move to folder `datasets`. An example datasets folder has the following structure:

```
datasets
├── Houston13
│   ├── Houston.mat
│   └── Houston_gt.mat
├── Houston18
│   ├── houston18_gt.npy
│   └── houston18_im.npy
├── PaviaU
│   ├── PaviaU.mat
│   ├── PaviaU_gt.mat
├── Salinas
│   ├── Salinas_corrected.mat
│   └── Salinas_gt.mat
├── dataset_config.json
```



## Usage

1. Download the required datasets and move to folder `datasets`.
2. Run `main.py`. 
