# unstained-renal-biopsy-segmenation

These experiments were carried out in the context of understanding the feasibility of segmenting unstained renal biopsy samples using state-of-the-art segmentation models such as U-Net, SAM and SAM2.

## Requirements
```
python >= 3.8
torch >= 2.0
torchvision
pillow
matplotlib
albumentations
opencv-python
scikit-learn
segmentation-models-pytorch
git+https://github.com/facebookresearch/segment-anything.git
git+https://github.com/facebookresearch/sam2.git
```
There is a command in the beginning of each notebook to install the respective requirements.

## Installation
1. Clone this repository: 
```
git clone https://github.com/marianaosiecka/unstained-renal-biopsy-segmentation.git
```

## Checkpoints 
For the fine-tuned U-Net, you can download the current best **checkpoints** at:
* [**u-net multi-class checkpoint**](https://drive.google.com/file/d/1_BFFzCs_zzK8QvQvZHZSJwQ3Dop11Ose/view?usp=sharing);
* [**u-net binary checkpoint**](https://drive.google.com/file/d/1V-c_O0LcaTrUOtMPIJt0vCYr53PBRAds/view?usp=sharing).


To run SAM's notebook, install the default checkpoint from [SAM's official repository](https://github.com/facebookresearch/segment-anything?tab=readme-ov-file#model-checkpoints) or directly from this [link](https://dl.fbaipublicfiles.com/segment_anything/sam_vit_h_4b8939.pth).


To use the checkpoints, download them and save them to the corresponding repository directory 'unstained-renal-biopsy-segmentation/deep-learning/u-net/checkpoints/' or 'unstained-renal-biopsy-segmentation/deep-learning/sam'.
