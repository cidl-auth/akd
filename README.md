# Trustworthy Knowledge Distillation via Anchor-Guided Distribution Learning

This repo is for reproducing the CIFAR-100 experimental results in our paper Trustworthy Knowledge Distillation via Anchor-Guided Distribution Learning.


To perform knowledge transfer from Resnet32x4 to Resnet8x4 on CIFAR-100 using AKD, run:

```sh
python train_cifar_student.py --path_t ./save/models/resnet32x4_vanilla/ckpt_epoch_240.pth --distill AKD --model_t resnet32x4 --model_s resnet8x4
```


## Acknowledgments

The work presented here is supported by the RoboSAPIENS project funded by the European Commission’s Horizon Europe programme under grant agreement number 101133807.
This publication reflects the authors’ views only. The European Commission is not responsible for any use that may be made of the information it contains.

<p align="center"> <img src="https://raw.githubusercontent.com/cidl-auth/mitigate-anomalies/main/assets/eu_funded.jpg" alt="Funded by the European Union" width="180"/> </p> <p align="center"> Learn more about <a href="https://robosapiens-eu.tech/" target="_blank"><strong>RoboSAPIENS</strong></a>. </p> <p align="center"> <img src="https://raw.githubusercontent.com/cidl-auth/mitigate-anomalies/main/assets/robosapiens_robot.png" alt="RoboSAPIENS" width="80"/> </p>
