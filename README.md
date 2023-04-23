## Multi Model Comparison Deep Learning Project

### [ModelV01](https://github.com/aatansen/Multi-Model-Comparison-Deep-Learning-Project/tree/main/ModelV01):
- Pretrained model is used
- freezing all layer except x number of layer (experimental)
- ImageDataGenerator is used for preprocessing images
- In output Softmax activation is used as it is multiclass
- Total num epochs : 50
- Adam optimizer is used with 0.0001 learning rate
- Dropout & early_stop function used to avoid overfitting.

### [ModelV02](https://github.com/aatansen/Multi-Model-Comparison-Deep-Learning-Project/tree/main/ModelV02):
- Changes
    - Rotation Range changed from 20 to 10
    - Width , Height shift &  zoom range changed from 0.2 to 0.1
    - Freezing all layer
    - Model saved based on max validation accuracy
    - Roboflow dataset is used (Previous ModelV01 was on Kaggle Dataset)
    - Total seven model is trained and measured
- Removed
    - Shear range Removed
    - Dropout, New layer (experimented previously)
    - Early stop function removed
- Added
    - Preprocessing function added
    - Shuffle added
- Advantage
    - Accuracy increased
    - Complexity reduced
    - Less number of params
    - Accurate ROC,AUC curve
    - Accurate performance matrices

### [ModelV03 (Final Project File)](https://github.com/aatansen/Multi-Model-Comparison-Deep-Learning-Project/tree/main/ModelV03%20(Final%20Project%20File)/Project%20Files):
- Changes
    - Kaggle and Roboflow both dataset is Measured separately
    - Roboflow dataset decreases after filtering
- Removed
    - Few number of images removed after filtering process
- Added
    - Image filtering added
    - labels added for image preview and other task
    - Total training time measured
    - Epoch number measured by highest training and validation accuracy
- Advantage
    - Black images detected
    - Two dataset models are compared
    - Accurate result analysis