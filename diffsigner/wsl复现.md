教程[link](https://www.yuque.com/sunsa-i3ayc/sivu7h/qw2eg7win8unbwn0)

- python
- venv
- pytorch
- git clone
- pip -r
- data
- cudann `sudo apt install nvidia-cudnn`
```
set PYTHONPATH=. 
set CUDA_VISIBLE_DEVICES=0 
python data_gen/binarize.py --config configs/acoustic/nomidi.yaml
python run.py --config configs/acoustic/nomidi.yaml --exp_name $MY_DS_EXP_NAME --reset
```
