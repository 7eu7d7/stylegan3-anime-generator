## StyleGAN3 anime picture generator<br><sub>Training with LoliHouse dataset</sub>

<p float="left">
  <img src="./imgs/seed0046.png" width="400" />
  <img src="./imgs/seed1119.png" width="400" /> 
  <img src="./imgs/seed0540.png" width="400" />
  <img src="./imgs/seed0334.png" width="400" />
</p>

## Introduction
The code is based on the official implementation [stylegan3](https://github.com/NVlabs/stylegan3), with some details modified.

Using a large number of full body anime character images to train which get an anime character generator.

Please refer to the official code for the usage of the model.

## Pre-trained models

|       <sub>Config</sub><br><br>        |    <sub>kimg</sub>    |  FID   |                link                |
|:--------------------------------------:|:---------------------:|:------:|:----------------------------------:|
|      <sub>StyleGAN3&#8209;R</sub>      |   <sub>10800</sub>    |  7.51  |   <sub>[kimg_10800.pkl](https://www.aliyundrive.com/s/tCpuaxr3v3D)</sub>    |
| <sub>StyleGAN3&#8209;R (stage2)</sub>  | <sub>10800+1600</sub> |  6.97  | <sub>[kimg_10800+1600.pkl](https://www.aliyundrive.com/s/tNR71W9hQfu)</sub> |


## LoliHouse Dataset

The training dataset was constructed based on the image package provided by LoliHouse. The 83,786 images obtained by randomly coring the images in the package by square boxes were used as the training dataset.

The resolution of the dataset is 1024x1024.

Dataset links: (Ali cloud disk has restrictions on sharing, so it is spread over two cloud disks)
* [LoliHouse Dataset p1](https://www.aliyundrive.com/s/Et1Xagopriw) Parts other than .z01 and .zip
* [LoliHouse Dataset p2](https://pan.xunlei.com/s/VMwanpwJcTsHEZ2PX58aWNjRA1) .z01 and .zip **code: qay7**

Original image package:
[LoliHouse](magnet:?xt=urn:btih:756e909170575bef7ac767222cc6c356c213c726&tr=http://open.acgtracker.com:1096/announce)

## Cite the Dataset

```bibtex
@misc{
  lolihouse2022,
  author = {ZiYi Dong},
  title = {LoliHouse Anime Character Dataset},
  howpublished = {\url{https://github.com/7eu7d7/stylegan3-anime-generator}},
  url = {https://github.com/7eu7d7/stylegan3-anime-generator},
  type = {dataset},
  year = {2022},
  month = {February}
}
```