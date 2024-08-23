# OnZeta
PyTorch Implementation for Our ECCV'24 Paper: "Online Zero-Shot Classification with CLIP"

## Requirements
* Python 3.9
* PyTorch 1.12
* [CLIP](https://github.com/openai/CLIP)

## Usage:
OnZeta with pre-trained ResNet-50
```
python main_online.py -a RN50 --data_path /path/to/imagenet
```

## Citation
If you use the package in your research, please cite our paper:
```
@inproceedings{qian2024onzeta,
  author    = {Qi Qian and
               Juhua Hu},
  title     = {Online Zero-Shot Classification with CLIP},
  booktitle = {The 18th European Conference on Computer Vision, {ECCV} 2024},
  year      = {2024}
}
