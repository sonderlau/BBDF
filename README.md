# BBDF: Brownian Bridge Diffusion Framework for Precipitation Nowcasting Correction

By Baitian Liu, Haiping Zhang, Xujian Fang.

This repo is the official implementation of BBDF, that will appear in GRL.



> Last update: 2025/10/26
>
> **Source code is pending on publication, please wait.**







## SEVIR Dataset

[Storm EVent ImageRy (SEVIR) dataset](https://sevir.mit.edu/) is a spatiotemporally aligned dataset containing over 10,000 weather events. We adopt NEXRAD Vertically Integrated Liquid (VIL) mosaics in SEVIR for benchmarking precipitation nowcasting, i.e., to predict the future VIL up to 60 minutes given 65 minutes context VIL. The resolution is thus 13×384×384→12×384×384.



## Citation

```
@article{BBDF2025,
  author = {Baitian, Liu and Haiping, Zhang and Xujian, Fang},
  title = {BBDF: Brownian Bridge Diffusion Framework for Precipitation Nowcasting Correction},
  journal = {Geophysical Research Letters},
  volume = {},
  number = {},
  pages = {},
  doi = {},
  url = {},
  year = {2025}
}

```





## Credit

Third-party libraries:

- [PyTorch](https://pytorch.org/)
- [PyTorch Lightning](https://www.pytorchlightning.ai/)



Open sources models:

- [BBDM](https://github.com/xuekt98/BBDM/tree/main) - MIT License
- [U-Net]() - 
- [Earthformer](https://github.com/amazon-science/earth-forecasting-transformer) - Apache-2.0 License
- [PredRNNv2](https://github.com/thuml/predrnn-pytorch) 
- [NowcastNet](https://doi.org/10.24433/CO.0832447.v1) - CC 1.0 Universal License
- [LightningDiT](https://github.com/hustvl/LightningDiT) - MIT License



