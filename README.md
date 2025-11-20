# Fruit-Classification
Project for Deep Learning for Image Recognition.

## Setup Colab for Collaborators
**Branches**: [Main](https://colab.research.google.com/github/garlicxd/Fruit-Classification/blob/main/Fruit_Classification_Project.ipynb), [Automation](https://colab.research.google.com/github/garlicxd/Fruit-Classification/blob/automation/Fruit_Classification_Project.ipynb)

1. Initialize the dataset using `kaggle.json` in the first block.
2. Set Parameters in the second block.

**To save progress to GitHub, simply `File > Save`**.

## TODO
- [ ] **Additional Visualization**
    - [x] Loss and Accuracy Diagram
    - [x] Confusion Matrix
    - [x] Data distribution bar chart
    - [ ] Augmentation check chart
    - [ ] Worst classifications
    - [ ] Saliency Maps / Class Activation Maps (Grad-CAM)
    - [ ] Print out all the parameters alongside the images
- [ ] **Automation**
    - [ ] Automate all parameters and their combinations with images. Save the plots and data outputs
- [ ] **Experiments**
    - [ ] Test with image augmentation - compare ours ✓, theirs, and none
    - [ ] Fine-Tune ResNet - unfreeze more than one layer
    - [ ] Compare Optimizers
    - [ ] Try different model architectures like MobileNet or EfficientNet
    - [ ] Custom classifier head - add multiple layers on top
    - [ ] Label smoothing: `criterion = nn.CrossEntropyLoss(label_smoothing=0.1)`
- [ ] **Paper**
    - [ ] Add to the paper that the dataset is well balanced
