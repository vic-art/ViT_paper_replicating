## ViT_paper_replicating
The aim of this project is to create a Vision Transformer (ViT) from scratch using PyTorch by replicating research paper ["An Image is Worth 16x16 Words: 
Transformers for Image Recognition at Scale"](https://arxiv.org/abs/2010.11929). 
Then we applied it to our FoodVision problem to classify different images of pizza, steak and sushi.

After that we took advange of transfer learning and applied a pretrained ViT from `torchvision.models` on the same dataset (for details, click [here](https://pytorch.org/vision/main/models/generated/torchvision.models.vit_b_16.html)) and compared the results. 



