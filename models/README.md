# Thesis Code

All model code is contained in this directory. There is a general template that is applied to all models with minor changes

## Template / Steps

| # | Step | Notes |
| --- | --- | --- |
| 1 | Import Libraries| The same libraries are used for all models
| 2 |  Setup Dataset| Everything is the same for all models exept IMG_Size. InceptionV3 had no resizing. Images for the other 4 models were resized to (224,224)
| 3 | Data Augmentation Function | The same for all models
| 4 | Define Model | Here the only thing that is different is base_model definition, pre-process function and for InceptionV3, Global Average Pooling was replaced with a flatten layer.
| 5 | Compile model | Same for all models|
| 6 | Define Callbacks | Same for all models, expect checkpoint and tensorboard directories, where each model had its own |
| 7 | Train Model | Trained Model with frozen layers exept classfier |
| 8 |  Fine Tune | Same for all models exept the number of layers that were fine tuned
| 9 | Compile model | After unfrozing some layers, I compiled the model again with the same optimizer but with a smaller Learning Rate
| 10 | Train model again | Trained model again for around 10 epochs
| 11 | Evaluation | All models were evaluated the same way
| 12* | ResNet101 Demo | At the end of this model, there's code where you can run predictions and see the result.


