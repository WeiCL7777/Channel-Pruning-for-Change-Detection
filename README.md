# Channel-Pruning-for-Change-Detection
对遥感图像任务——变化检测（CD）进行结构化通道剪枝
## Pruning
运行 prune 文件夹中的 jupyter 文件，对 resnet50 进行通道剪枝
## Train
```
python train.py --backbone 'resnet' --dataset 'levir' --mode 'rsp_300'
```
## Eval
```
python eval.py --backbone 'resnet' --dataset 'levir' --mode 'rsp_300' --path [model path]
```
## Visualization
```
python visualization.py --backbone 'resnet' --dataset 'levir' --mode 'rsp_300' --path [model path]
```
## Reference
The codes are mainly borrowed from https://github.com/ViTAE-Transformer/RSP.git and https://github.com/VainF/Torch-Pruning.git
