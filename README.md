# A STRONG BASELINE FOR VEHICLE RE-IDENTIFICATION
This repo is strong baseline for Vechicle Re-identification in Track 2 Ai-City challenge.

We base on 2nd place solution in last Ai-City challenge: "https://github.com/Xiangyu-CAS/AICity2020-VOC-ReID"

## INTRODUCTION

Our proposed method sheds light on three main factors that contribute most to the performance, including:(1) minizing the gap between real and synthetic data, (2) network modification by stacking multi heads with attention mechanism to backbone, (3) adaptive loss weight adjustment.

## INSTALLATION
1. pytorch>=1.2.0
2. yacs
3. [apex](https://github.com/NVIDIA/apex) (optional for FP16 training, if you don't have apex installed, please turn-off FP16 training by setting SOLVER.FP16=False)
````
$ git clone https://github.com/NVIDIA/apex
$ cd apex
$ pip install -v --no-cache-dir --global-option="--cpp_ext" --global-option="--cuda_ext" ./
````
4. python>=3.7
5. cv2

## REPRODUCE THE RESULT ON AICITY 2020 CHALLENGE
