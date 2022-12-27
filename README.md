# Awesome Diffusion Models in Low-Level Vision [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
A curated list of awesome diffusion models in low-level vision papers, inspired by [awesome-NeRF](https://github.com/yenchenlin/awesome-NeRF).

## Contributing
Please feel free to send us pull requests or email us to add links.


## Table of Contents

- [Papers](#papers)
- [Implementations](#implementations) 

## Papers

#### Diffusion Model
- [Image Super-Resolution via Iterative Refinement](https://arxiv.org/abs/2104.07636), Chitwan Saharia et al., arxiv 2021 | [Github](https://github.com/Janspiry/Image-Super-Resolution-via-Iterative-Refinement) 

- [High-Resolution Image Synthesis with Latent Diffusion Models](https://arxiv.org/abs/2112.10752), Robin Rombach et al., CVPR 2022 | [Github](https://github.com/CompVis/latent-diffusion)

- [Denoising Diffusion Restoration Models](https://arxiv.org/abs/2201.11793), Bahjat Kawar et al., ICLRW 2022 | [Github](https://github.com/bahjat-kawar/ddrm)

- [Improving Diffusion Models for Inverse Problems using Manifold Constraints](https://arxiv.org/abs/2206.00941), Hyungjin Chung et al., NeurIPS 2022 | [Github](https://github.com/HJ-harry/MCG_diffusion)

#### Faster Inference
- [Neural Sparse Voxel Fields](https://lingjie0206.github.io/papers/NSVF/), Liu et al., NeurIPS 2020 | [github](https://github.com/facebookresearch/NSVF) | [bibtex](./NeRF-and-Beyond.bib#L135-L141) <!---Liu20neurips_sparse_nerf-->


#### Faster Training
- [Depth-supervised NeRF: Fewer Views and Faster Training for Free](https://arxiv.org/pdf/2107.02791.pdf), Deng et al., Arxiv 2021 | [github](https://github.com/dunbar12138/DSNeRF) | [bibtex](./citations/dsnerf.txt)
- [Direct Voxel Grid Optimization: Super-fast Convergence for Radiance Fields Reconstruction](https://arxiv.org/abs/2111.11215.pdf), Sun et al., Arxiv 2021 | [github](https://github.com/sunset1995/DirectVoxGO) | [bibtex](./citations/DirectVoxGO.txt) <!---sun2021direct-->

#### Unconstrained Images
- [NeRF in the Wild: Neural Radiance Fields for Unconstrained Photo Collections](https://nerf-w.github.io/), Martin-Brualla et al., CVPR 2021 | [bibtex](./NeRF-and-Beyond.bib#L152-L158) <!---MartinBrualla20arxiv_nerfw-->
- [Ha-NeRF:laughing:: Hallucinated Neural Radiance Fields in the Wild](https://rover-xingyu.github.io/Ha-NeRF/), Chen et al., Arxiv 2021 | [github](https://github.com/rover-xingyu/Ha-NeRF) | [bibtex](./citations/Ha-NeRF.txt) <!---chen2021hallucinated-->

## Implementations
#### Tensorflow
- [NeRF](https://github.com/bmild/nerf), Mildenhall et al., 2020 | [bibtex](./NeRF-and-Beyond.bib#L168-L173)

#### PyTorch
- [NeRF-PyTorch](https://github.com/yenchenlin/nerf-pytorch), Yen-Chen Lin, 2020 | [bibtex](./citations/pytorch-nerf.txt)
- [NeRF-PyTorch-Lighting](https://github.com/kwea123/nerf_pl), [@kwea123](https://github.com/kwea123), 2020
- [NeRF-W](https://github.com/kwea123/nerf_pl/tree/nerfw), [@kwea123](https://github.com/kwea123), 2021
- [NeRF-PyTorch3D](https://github.com/facebookresearch/pytorch3d/tree/master/projects/nerf), [@facebookresearch](https://github.com/facebookresearch), 2020

#### Jax
- [JaxNeRF](https://github.com/google-research/google-research/tree/master/jaxnerf), Deng et al., 2020 | [bibtex](https://github.com/yenchenlin/awesome-NeRF/blob/main/NeRF-and-Beyond.bib#L55-L60)
- [Mip-NeRF](https://github.com/google/mipnerf), [@google](https://github.com/google), 2021 | [bibtex](./citations/mipnerf.txt)

## License 
MIT
