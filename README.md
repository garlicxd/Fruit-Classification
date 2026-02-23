# Fruit-Classification
Project for Deep Learning for Image Recognition.

## Setup Colab for Collaborators
**Branches**: [Main](https://colab.research.google.com/github/garlicxd/Fruit-Classification/blob/main/Fruit_Classification_Project.ipynb)

1. Initialize the dataset using `kaggle.json` in the first block.
2. Set Parameters in the second block.

**To save progress to GitHub, simply `File > Save`**.

## TODO
- [X] **Additional Visualization**
    - [x] Loss and Accuracy Diagram
    - [x] Confusion Matrix
    - [x] Data distribution bar chart
    - [X] Augmentation check chart
    - [X] Worst classifications
    - [X] Saliency Maps / Class Activation Maps (Grad-CAM)
    - [X] Print out all the parameters alongside the images
- [X] **Automation**
    - [X] Automate all parameters and their combinations with images. Save the plots and data outputs
- [X] **Experiments**
    - [X] Test with image augmentation - compare ours ✓, theirs, and none
    - [X] Fine-Tune ResNet - unfreeze more than one layer
    - [X] Compare Optimizers
    ~~Try different model architectures like MobileNet or EfficientNet~~
    - [X] Custom classifier head - add multiple layers on top
    - [X] Label smoothing: `criterion = nn.CrossEntropyLoss(label_smoothing=0.1)`
