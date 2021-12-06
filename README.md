# IGD
Code for 'Deep One-Class Classification via Interpolated Gaussian Descriptor'

Accepted at AAAI 2022. 

Code will be released later. 


# RTFM
This repo contains the Pytorch implementation of our paper:
> [**Deep One-Class Classification via Interpolated Gaussian Descriptor**](https://arxiv.org/pdf/2101.10043.pdf)
>
> Yuanhong Chen*, [Yu Tian*](https://yutianyt.com/), [Guansong Pang](https://sites.google.com/site/gspangsite/home?authuser=0), [Gustavo Carneiro](https://cs.adelaide.edu.au/~carneiro/).

- **Accepted at AAAI 2022.**  

- **SOTA on 6 benchmarks.** Check out [**Papers With Code**](https://paperswithcode.com/task/anomaly-detection). 


## Code will be released soon.  

<!-- 
**Please download the extracted I3d features for ShanghaiTech and UCF-Crime dataset from links below:**

> [**ShanghaiTech train i3d onedirve**](https://uao365-my.sharepoint.com/:f:/g/personal/a1697106_adelaide_edu_au/EiLi_oBQnAFCq3UG184p_akB2sV7szCWvOV9PtaKJ6lxtQ?e=MeM3TE)
> 
> [**ShanghaiTech test i3d onedrive**](https://uao365-my.sharepoint.com/:f:/g/personal/a1697106_adelaide_edu_au/EvUUrWqpWqVHrXBzxbzAdD8BGiZBiumWWOaZmQ_AMAkAdg?e=P1rwCg)
> 
> [**ShanghaiTech train features on Google dirve**](https://drive.google.com/drive/folders/1z-CQPpVtTyfZyPKZdv2hZ-h2oMF6s8ep?usp=sharing)
> 
> [**ShanghaiTech test features on Google dirve**](https://drive.google.com/drive/folders/1L71Qa0gao6aLVhSjL0H-u2khmTRKcmQs?usp=sharing)
> 
> [**checkpoint for ShanghaiTech**](https://drive.google.com/file/d/1epISwbTZ_LXKfJzfYVIVwnxQ6q49lj5B/view?usp=sharing)

**Extracted I3d features for UCF-Crime dataset**

> [**UCF-Crime train i3d onedirve**](https://uao365-my.sharepoint.com/:f:/g/personal/a1697106_adelaide_edu_au/ErCr6bjDzzZPstgposv1ttYBudL8UVnap6eHS46fFbooAQ?e=RZsMtA)
> 
> [**UCF-Crime test i3d onedrive**](https://uao365-my.sharepoint.com/:f:/g/personal/a1697106_adelaide_edu_au/EsmBEpklrShEjTFOWTd5FooBVXbeoDHTTqPZn60Vj3Guhg?e=hvv46w)
> 
> [**UCF-Crime train I3d features on Google drive**](https://drive.google.com/file/d/16LumirTnWOOu8_Uh7fcC7RWpSBFobDUA/view?usp=sharing)
> 
> [**UCF-Crime test I3d features on Google drive**](https://drive.google.com/drive/folders/1QCBTDUMBXYU9PonPh1TWnRtpTKOX-fxr?usp=sharing)
> 
> [**checkpoint for Ucf-crime**](https://uao365-my.sharepoint.com/:u:/g/personal/a1697106_adelaide_edu_au/Ed0gS0RZ5hFMqVa8LxcO3sYBqFEmzMU5IsvvLWxioTatKw?e=qHEl5Z)

The above features use the resnet50 I3D to extract from this [**repo**](https://github.com/Tushar-N/pytorch-resnet3d).

Follow previous works, we also apply 10-crop augmentations. 

The following files need to be adapted in order to run the code on your own machine:
- Change the file paths to the download datasets above in `list/shanghai-i3d-test-10crop.list` and `list/shanghai-i3d-train-10crop.list`.
- Feel free to change the hyperparameters in `option.py`
### Train and test the RTFM
After the setup, simply run the following command: 
```shell
python main.py
```
 -->

## Citation

If you find this repo useful for your research, please consider citing our paper:

```bibtex
@misc{chen2021deep,
      title={Deep One-Class Classification via Interpolated Gaussian Descriptor}, 
      author={Yuanhong Chen and Yu Tian and Guansong Pang and Gustavo Carneiro},
      year={2021},
      eprint={2101.10043},
      archivePrefix={arXiv},
      primaryClass={cs.CV}
}
```
---