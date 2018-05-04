## A Stagewise Refinement Model for Detecting Salient Objects in Images (SRM)
This package has the source code for the paper "A Stagewise Refinement Model for Detecting Salient Objects in Images" (ICCV17).

## Citing this work
If you find this work useful in your research, please consider citing:

     @inproceedings{wangiccv17,
        Author={Wang, Tiantian and Borji, Ali and Zhang, Lihe and Zhang, Pingping and Lu, Huchuan},
        Title={A Stagewise Refinement Model for Detecting Salient Objects in Images},
        Booktitle={Proceedings of the IEEE International Conference on Computer Vision},
        Year={2017}
     }

## Note:
* We use [Caffe](https://github.com/hszhao/PSPNet) to train our Stagewise Refinement Model.
* Our Resnet-50 model is based on the previous work [simon2016cnnmodels](https://arxiv.org/pdf/1612.01452.pdf).
* Saliency maps are generated without any pre- or post-processing.

## Test
* Please run `test.m` to generate saliency maps in the `./saliency_map` folder. 

## Download
* Our initialized models and trained models can be found in [Baidu drive](http://pan.baidu.com/s/1i4SDbdb) or [Google drive](https://drive.google.com/file/d/0B_MpGgTntG47eDRfd0JzcnFBT00/view?usp=sharing).
* The saliency maps on 10 datasets including ECSSD, PASCAL-S, SOD, SED1, SED2, MSRA, DUT-OMRON, THUR15K, HKU-IS and DUTS can be found in [Baidu drive](https://pan.baidu.com/s/1ugcMJ252awPpl5k0EkfpHg) or [Google drive]().


## Contact
tiantianwang.ice@gmail.com



