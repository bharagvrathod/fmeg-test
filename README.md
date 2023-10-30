# Facial Micro-Expression Generation based on Deep Motion Re-targeting and Transfer Learning alongside case study of second order motion model

by Xinqi Fan, Ali Shahid, and Hong Yan original authors modified by Bhargav Rathod 

## Introduction
This repository is for our work Facial Micro-Expression Generation based on Deep Motion Re-targeting and Transfer Learning.

## Usage
### Requirement
Python 3.8

please check the requirements.txt


### Download
Clone the repository:
```
git clone https://github.com/bharagvrathod/fmeg-test
cd FMEG
```

### Prepare data

* Please download CASME, SMIC, and SAMM.
* Modify the path to your dataset in the following config/camse-256.yaml, config/smic-256.yaml, config/samm-256.yaml.

### Pretrained weights

* Please find them [here](https://portland-my.sharepoint.com/:f:/g/personal/xinqifan2-c_my_cityu_edu_hk1/EibgTr1yER1JsLGSBW51mBwBIyboyjSD7YviDfznM56Dow?e=seGxEb)

### Train the model

* Please refer to train.sh and modify the related checkpoint path.

### Test the model

* Please refer to demo.sh and modify the related paths.
* Please refer to second_order_demo.sh and modify the related paths.
* The pretrained weights can be found in the above mentioned links.

## Citation
To be updated

## Comment
We welcome any pull request for improving the code.


