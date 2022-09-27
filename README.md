# Developing and evaluating 5 different models on COVID-19 recognition

## The models that were used are:

- ResNet50
- ResNet101
- DenseNet121
- DenseNet169
- Inception V3

## Installing required libraries

To setup required libraries use pip with the file ***requirements.txt***

---

## Code

Code is available in the ***models*** folder for each model.

## Thesis

Thesis document is available in the ***thesis*** folder.

## Directory Structure:

	- board_logs
		- Contains tensorboard files for all models
	- checkpoints
		- Contains checkpoints during training for all models
	- Dataset
		- Contains the data that was used for training, validation and evaluation
		- lung_masks:
			- Lung masks for each image that were not used yet.
	- logs
		- Contains training logs for each model during training from model.fit()
	- models
		- Jupyter Notebooks for each model
	- Thesis
		- Contains thesis

For any questions send an email to ***mariosconsta@gmail.com***