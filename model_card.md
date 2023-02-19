# Model Card


## Model Description

**Input:** 150x150 colored images

**Output:** Prediction of what category the image is.

**Model Architecture:** CNN with a convolutional input layer, three convolutional hidden layers, two dense hidden layers and one output layer.


## Performance

![Model Accuracy and Loss](https://github.com/sdarwish13/PCMLAI/blob/main/Model%20Accuracy%20and%20Loss.png?raw=true)


## Limitations

* If the images in the dataset are low resolution, noisy, or contain occlusions, the model may struggle to accurately classify them.
* If the objects in the images are highly variable in terms of shape, size, orientation, and lighting, it may be difficult for the model to accurately classify them.
* If the training dataset contains bias, such as an over-representation of certain classes, the resulting model may not perform well on new, unseen data that is not biased in the same way.


## Trade-offs

* Training time vs. accuracy: Longer training times may lead to higher accuracy, but at the cost of increased time and resource usage.
* Number of classes vs. accuracy: Adding more classes to a classification problem can increase the complexity of the problem and potentially decrease accuracy.
* Model complexity vs. accuracy: A more complex model may be able to achieve higher accuracy, but at the cost of longer training times and greater computational resources.
