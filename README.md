## Neural Style Transfer (optimization method) :computer: + :art: = :heart:
This repo contains a concise PyTorch implementation of the original NST paper (:link: [Gatys et al.](https://www.cv-foundation.org/openaccess/content_cvpr_2016/papers/Gatys_Image_Style_Transfer_CVPR_2016_paper.pdf)).

This repo is a copy of Gordić Aleksa with some further improvements like visualization of feature maps and gram matrix for the optimizing image and using a layer 1 content feature map because that worked better for me and also i changed the weights of tv, content and style which I found better also this repo now supports using 2 style images instead of 1.

Below are some of the images created using this 
<img src="data\output-images\combined_Dhruv_final_pic_wave_crop_edtaonisl_alpha-60\Dhruv_final_pic_wave_crop_edtaonisl_alpha0.6 _o_adam_i_content_h_400_m_vgg19_cw_1000000.0_sw_20000.0_tv_1000.0.jpg" width="270px">

<img src="data\output-images\combined_Dhruv_final_pic_edtaonisl\2999.jpg" width="270px">

```
@misc{Gordić2020nst,
  author = {Gordić, Aleksa},
  title = {pytorch-neural-style-transfer},
  year = {2020},
  publisher = {GitHub},
  journal = {GitHub repository},
  howpublished = {\url{https://github.com/gordicaleksa/pytorch-neural-style-transfer}},
}
```

## Licence

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://github.com/gordicaleksa/pytorch-neural-style-transfer/blob/master/LICENCE)