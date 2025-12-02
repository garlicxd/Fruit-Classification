# Fruit-Classification
Project for Deep Learning for Image Recognition.

## Setup Colab for Collaborators
**Branches**: [Main](https://colab.research.google.com/github/garlicxd/Fruit-Classification/blob/main/Fruit_Classification_Project.ipynb), [Automation](https://colab.research.google.com/github/garlicxd/Fruit-Classification/blob/automation/Fruit_Classification_Project.ipynb)

### Solo Run
1. Load Functions by running the first codeblock
2. Set Default Config
   - Default Values
   - Naming Scheme
3. Run Default Config, outputs in solo run folder

### Run All
1. Load Functions by running the first codeblock
2. Set Default Config
   - Default Values
   - Naming Scheme
3. Setup Value options, by filling out the grid. (Key names follow Default Config)
4. Run Cell - outputs in folder experiment_x

**To save progress to GitHub, simply `File > Save`**.

## TODO
- [X] **Additional Visualization**
    - [x] Loss and Accuracy Diagram
    - [x] Confusion Matrix
    - [x] Data distribution bar chart
    - [X] Print out all the parameters alongside the images
- [X] **Automation**
    - [X] Automate all parameters and their combinations with images. Save the plots and data outputs
- [ ] **Experiments**
    - [x] Test with image augmentation - compare ours ✓, theirs, and none
    - [x] Patience for training - stopping after no improvement (early stopping implemented)
    - [ ] Fine-Tune ResNet - unfreeze more than one layer
    - [x] Compare Optimizers
    - [ ] Try different model architectures like MobileNet or EfficientNet
