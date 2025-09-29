# **ViT Flower Classification**

This project implements a Vision Transformer (ViT) model for flower image classification using PyTorch.

## **Features**

- Leverages **self-attention** with Vision Transformer (ViT) for image classification.  
- Supports **custom datasets** with **data augmentation** and batching.  
- Includes **training/eval pipeline** with **cosine LR scheduler**, **layer freezing**, and **TensorBoard** logging.  
- Provides **pretrained weights** support for transfer learning.  

## **Usage**

1. Install dependencies:  
   ```bash
   pip install -r requirements.txt
   
2. Prepare dataset: Download flower dataset and extract to flower_photos/.

3. Train the model: python train.py --data-path /path/to/flower_photos --weights ./vit_base_patch16_224_in21k.pth

4. Predict a single image: python predict.py

## **Future Improvements**

- Experiment with larger ViT models (ViT-L/16, ViT-H/14).

- Optimize training strategies and data augmentation.

- Extend to multi-dataset classification or cross-domain tasks.
