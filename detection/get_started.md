# Focal Transformer for Object Detection

This page explains the details for using Focal Transformers as the backbone for object detection on COCO. 
We build object detection models based on [mmdetection](https://github.com/open-mmlab/mmdetection). 
More specifically, we follow [Swin-Transformer-Object-Detection](https://github.com/SwinTransformer/Swin-Transformer-Object-Detection) to set up our pipelines. 
We will release the model script soon later. Stay tuned!


# HotFix
CUDA_RuntimeError: radix_sort: failed on 1st step: cudaErrorInvalidDevice: invalid device ordinal

Error in torch==1.8.0 --> torch==1.8.1
