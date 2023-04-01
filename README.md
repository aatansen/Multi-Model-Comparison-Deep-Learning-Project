## Multi Model Comparison Deep Learning Project

### [ModelV01](https://github.com/aatansen/Multi-Model-Comparison-Deep-Learning-Project/tree/main/ModelV01):
- Pretrained model is used
- freezing all layer except x number of layer (experimental)
- ImageDataGenerator is used for preprocessing images
- In output Softmax activation is used as it is multiclass
- Total num epochs : 50
- Adam optimizer is used with 0.0001 learning rate
- Dropout & early_stop function used to avoid overfitting.