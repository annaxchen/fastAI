I'm currently working through the fast.AI course by Jeremy Howard. These are my notes and takeaways from the class.

Reading:
-  Practical Deep Learning for Coders with fastai and PyTorch

Process for Image Recog Training

Step 1: gather images for classification

Step 2: 

Train Model -> training set (resize inputs usually squish) -> checks parent folder for accuracy -> dataloaders feed training algorithm with images in "batch" on resnet (architecture)

Transfer Learning: use pretrained model and then fine-tune using fine_tune method in fastai
