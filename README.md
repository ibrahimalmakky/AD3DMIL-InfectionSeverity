# Attention Based Deep 3D Multiple Instance Learning for COVID-19 Infection Severity Classification

## Prerequisites:

Requirements available in "./requirements.txt". Install using:
```
pip3 install -r requirements.txt
```

## Dataset:

You need to provide the text lists of training, validation, and testing raw 3D CT files in "./dataset". 

For the raw CT files, we are using the [HUST dataset](https://ngdc.cncb.ac.cn/ictcf/HUST-19.php) of CT images and clinical features for COVID-19. For ease of use you can download the pre-processed dataset from the following [link](https://mbzuaiac-my.sharepoint.com/:u:/g/personal/ibrahim_almakky_mbzuai_ac_ae/ERclV2NAX4FAlcjG7-SQ-Q4Bx22FCv0qn3Z5fgFaS4Qicg?e=M3bTYc).
You can also download the train, validation, and test splits from this [link](https://mbzuaiac-my.sharepoint.com/:f:/g/personal/ibrahim_almakky_mbzuai_ac_ae/EtANy0LHXBFNp9Knn7hCil8BQ4z9a-Mx8HN3dWP0DVTa7Q?e=fcd1Nc).

## Training:

1. Segmentation of lung masks: preprocess/seg.py for binary classification and preprocess/seg-multi-class.py for multi-class classification;
2. Training AD3D-MIL models: train.py for binary classification and train-mc.py for multi-class classification;
3. Testing: test.py for binary classification and test-mc.py for multi-class classification;

Note: You may modify the path or parameters in the corresponding locations.

## Citation:

If you use this code for your research, please consider citing:

@ARTICLE{9098062,
  author={Z. {Han} and B. {Wei} and Y. {Hong} and T. {Li} and J. {Cong} and X. {Zhu} and H. {Wei} and W. {Zhang}},
  journal={IEEE Transactions on Medical Imaging}, 
  title={Accurate Screening of COVID-19 Using Attention-Based Deep 3D Multiple Instance Learning}, 
  year={2020},
  volume={39},
  number={8},
  pages={2584-2594},}

## Contact
If you have any problem about our code, feel free to contact hanzhongyicn@gmail.com.