# Attention Based Deep 3D Multiple Instance Learning for COVID-19 Infection Severity Classification

## Prerequisites:

Requirements available in "./requirements.txt". Install using:
```
pip3 install -r requirements.txt
```

## Dataset:

You need to provide the text lists of training, validation, and testing raw 3D CT files in "./dataset".

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