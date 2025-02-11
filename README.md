# computer-vision-Python-PyTorch

### First
The model defined in `deep_CNN_from_scratch.ipynb` (model 2) had a significant overall performance against the model defined in `CNN_from_scratch.ipynb` (model 1).
This is due to the following reasons:
1. Model 2 is deeper; meaning it contains more <ins>convolutional layers</ins>, which enables the model to capture more features when training.
2. A couple of <ins>hyperparamaters</ins> are tuned in model 2: <ins>Batch size</ins> is changed from 4 to 16, and number of <ins>epochs</ins> is changed from 10 to 30.
3. A <ins>learning rate scheduler</ins> is defined and used in model 2, which allows the model to initially take larger steps to explore the solution space and then gradually decrease the step size as it approaches the optimal solution, leading to faster convergance and improved <ins>generalization</ins> performance.

### Second
The following notebooks
- `ResNet_AlexNet_single_label_class.ipynb`, and
- `ResNet_AlexNet_multi_label_class.ipynb`,
focus on investigating and experiencing open-source <ins>pretrained model</ins>, eventually leading to the world of <ins>transfer learning</ins>.
