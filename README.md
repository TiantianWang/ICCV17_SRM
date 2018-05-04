## A Stagewise Refinement Model for Detecting Salient Objects in Images (SRM)
This package has the source code for the paper "A Stagewise Refinement Model for Detecting Salient Objects in Images" (ICCV17).

## Paper link
* The paper can be found in [Baidu drive](https://pan.baidu.com/s/1xsWs-v80s4CQJOl_ouq3NA) or [Google drive](https://drive.google.com/open?id=0B_MpGgTntG47b18yUlJxOGtuNDA).

## Note
* We use [Caffe](https://github.com/hszhao/PSPNet) to train our Stagewise Refinement Model.
* Our Resnet-50 model is based on the previous work [simon2016cnnmodels](https://arxiv.org/pdf/1612.01452.pdf)[Imagenet pretrained models with batch normalization].
* Saliency maps are generated without any pre- or post-processing.

## How to use
Train
* Download our initialized model from [Baidu drive](https://pan.baidu.com/s/1UDIoe6Sp9tS6cNEt5PryGA) or [Google drive](https://drive.google.com/open?id=1VjBKqOwqpxeFoVjCxd9ueiuR63CB5u_P).
* Use the code in `./train` to train the network.

Test
* Download our trained model from [Baidu drive](https://pan.baidu.com/s/1Xp2T4J0k-5haiMlf4w3EEQ) or [Google drive](https://drive.google.com/open?id=1J4vDCihL-yism_Dn3J_dhgV9EH3a0Mia).
* Run `./test/test.m` to generate saliency maps in the `./saliency_map` folder. 

## Download
* The saliency maps on 10 datasets including ECSSD, PASCAL-S, SOD, SED1, SED2, MSRA, DUT-OMRON, THUR15K, HKU-IS and DUTS can be found in [Baidu drive](https://pan.baidu.com/s/1ugcMJ252awPpl5k0EkfpHg) or [Google drive]().

## Citing this work
If you find this work useful in your research, please consider citing:

     @inproceedings{wangiccv17,
        author={Wang, Tiantian and Borji, Ali and Zhang, Lihe and Zhang, Pingping and Lu, Huchuan},
        title={A Stagewise Refinement Model for Detecting Salient Objects in Images},
        booktitle = {The IEEE International Conference on Computer Vision (ICCV)},
        year = {2017}
     }
     

## Contact
tiantianwang.ice@gmail.com



