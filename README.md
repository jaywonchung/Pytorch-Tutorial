# Pytorch-Tutorial
Pytorch tutorial with jupyter notebook

# Installing prerequisites

- ```pip install jupyter```
- ```pip install torch```
- ```pip install torchvision```
- ```pip install tqdm```

# How to run this tutorial

1. Download the files in ```/Pytorch Tutorial``` to any folder.
2. Open your favorite shell, and ```cd``` to that folder.
3. Run ```jupyter notebook```
4. Shift+Enter through each notebook.

# Table of Content

1. Tensors and Dynamic Graphs
    - Basic Operations involving ```torch.Tensor```
    - Introduction to the dynamic computational graphs of ```torch.Autograd```
2. Modules and Custom Models
    - Adding predefined modules from ```torch.nn``` to ```torch.nn.Sequential```
    - Creating custom models by inheriting ```torch.nn.Module```
3. Training and Evaluating a Model
    - General training setup for cpu or cuda
    - Managing and loading predefined/custom datasets
    - Experiencing the conventions of training and evaluating (actually train a CNN to accuracy 96%)
4. Saving and Loading Model States
    - Using predefined models in ```torchvision.models```
    - Saving and loading model/optimizer parameters
