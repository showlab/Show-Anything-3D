# Show-Anything-3D
![image](https://user-images.githubusercontent.com/37300524/232230963-7aa69779-9752-4c92-8e39-4df210ecc5a7.png)
Edit and Generate Anything in 3D world!

The motivation of this repo: Segment Anything offers powerful perception capabilities and interfaces with points and boxes. We believe that the interface ability has the potential to greatly drive the development of generation and editing applications in 3D world. We will be posting some application developments from our lab here that are compatible with both Segment Anything and Generation, thanks.

# Anything with EG3D

We combine SAM with EG3D model to generate the view consistency video of any person in one image. We choose HFGI3D model to inverse the latent code and generate the video. 
<img width="974" alt="face" src="https://user-images.githubusercontent.com/37300524/232232719-1bb81681-4495-4d9f-a9d4-ced3617e285e.png">


https://user-images.githubusercontent.com/37300524/232232693-ad3b0329-ab83-48e1-8f7e-dca9dff7b32e.mp4


# Acknowledgements

[Segment Anything](https://github.com/facebookresearch/segment-anything)

[HFGI-3D](https://github.com/jiaxinxie97/HFGI3D)


# Citation
If you find this project helpful for your research, please consider citing the following BibTeX entry.
```
@article{kirillov2023segany,
  title={Segment Anything}, 
  author={Kirillov, Alexander and Mintun, Eric and Ravi, Nikhila and Mao, Hanzi and Rolland, Chloe and Gustafson, Laura and Xiao, Tete and Whitehead, Spencer and Berg, Alexander C. and Lo, Wan-Yen and Doll{\'a}r, Piotr and Girshick, Ross},
  journal={arXiv:2304.02643},
  year={2023}
}

@article{xie2022high,
  title={High-fidelity 3D GAN Inversion by Pseudo-multi-view Optimization},
  author={Xie, Jiaxin and Ouyang, Hao and Piao, Jingtan and Lei, Chenyang and Chen, Qifeng},
  journal={arXiv preprint arXiv:2211.15662},
  year={2022}
}

```








