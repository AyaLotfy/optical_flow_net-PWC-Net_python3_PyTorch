# optical_flow_net-PWC-Net_python3_PyTorch

This is the implementation of  the "FlowNet: Learning Optical Flow with Convolutional Networks" paper. It constructs appropriate CNNs which are capable of solving the optical flow estimation problem using Python 3.6, PyTorch and runs on the GPU of colab.

## Installation

The code was developed using Python 3.6 & PyTorch 1.4.0 & CUDA 10.1, using colab.

## Test

* Test the code: execute ```Optical flow python3 pytorch.ipynb```. You can set your input images by setting the variables 'im1_fn' and ```im1_fn```. You can set the directory of the .flo output by setting the variable ```flow_fn```.
* pwc_net.pth.tar is the fine-tuned weight on MPI Sintel

## Running the tests

* Input 1
![Image1](https://drive.google.com/file/d/1GB_yXCXr0Ibe_UOkM9F5xxD99EUmSARp/view?usp=sharing)
* Input 2
![Image2](https://drive.google.com/file/d/1OxxvZ3X-su78Cqbv4UtWS1HxzxQQ-x-b/view?usp=sharing)
* Ground Truth
![ground_truth](https://drive.google.com/file/d/1-Yyr9x24_fgaQd5DnbeeBuZUzlGmrwCA/view?usp=sharing)
* Output .flo file
[frame_output.flo](https://drive.google.com/file/d/1FERILJNlyTFUiAyJeP3cZ0lmgohqghIY/view?usp=sharing)
* Output .png image
![png](https://drive.google.com/file/d/1v-7VXzyf-pt8tF0pIaSngHZX6FE7yw8G/view?usp=sharing)

## Acknowledgments

* Thanks to Dr. Marwan Torki for explaining to me how the correlation works

## Contact

Aya Lotfy (ayalotfy2019@gmail.com) 

### Related Work

* [PWC-Net](https://github.com/NVlabs/PWC-Net)
* [PReMVOS](https://github.com/JonathonLuiten/PReMVOS)


### Paper & Citation

```
@inproceedings{DFIB15,
  author       = "A. Dosovitskiy and P. Fischer and E. Ilg and P. H{\"a}usser and C. Haz\ırba\ş and V. Golkov and P. v.d. Smagt and D. Cremers and T. Brox",
  title        = "FlowNet: Learning Optical Flow with Convolutional Networks",
  booktitle    = "IEEE International Conference on Computer Vision (ICCV)",
  month        = "Dec",
  year         = "2015",
  url          = "http://lmb.informatik.uni-freiburg.de/Publications/2015/DFIB15"
}
```
