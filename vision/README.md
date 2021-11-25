# HypMix + Cutout for Vision

First, install requirements.txt
```
pip install -r requirements.txt
```

### How to run experiments for CIFAR10
```
python main.py --dataset cifar10 --data_dir data/cifar10/ --root_dir experiments/ --labels_per_class 10 --arch preactresnet18  --learning_rate 0.1 --momentum 0.9 --decay 0.0001 --epochs 2000 --schedule 500 1000 1500 --gammas 0.1 0.1 0.1 --train mixup_hidden --mixup_alpha 2.0 --num_holes 2 --hole_length 4
```
