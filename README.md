# computer-vision-Python-PyTorch

Checkpoint:
The model defined in `deep_CNN_from_scratch.ipynb` (model 2) had a significant overall performance against the model defined in `CNN_from_scratch.ipynb` (model 1).
This is due to the following reasons:
1. Model 2 is deeper; meaning it contains more convolutional layers, which enables the model to capture more features when training.
2. A couple of hyperparamaters are tuned in model 2: Batch size is changed from 4 to 16, and number of epochs is changed from 10 to 30.
3. A learning rate scheduler is defined and used in model 2, which allows the model to initially take larger steps to explore the solution space and then gradually decrease the step size as it approaches the optimal solution, leading to faster convergance and improved generalization performance.
