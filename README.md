# Mask Detection

# Data:

[Face-mask detection](https://www.kaggle.com/datasets/sanknn/facemask-detection)

# Model:

```
Model: "sequential_1"
_________________________________________________________________
 Layer (type)                Output Shape              Param #
=================================================================
 sequential (Sequential)     (None, 180, 180, 3)       0

 rescaling_1 (Rescaling)     (None, 180, 180, 3)       0

 conv2d_3 (Conv2D)           (None, 178, 178, 16)      448

 max_pooling2d_3 (MaxPooling  (None, 89, 89, 16)       0
 2D)

 conv2d_4 (Conv2D)           (None, 87, 87, 32)        4640

 max_pooling2d_4 (MaxPooling  (None, 43, 43, 32)       0
 2D)

 conv2d_5 (Conv2D)           (None, 41, 41, 64)        18496

 max_pooling2d_5 (MaxPooling  (None, 20, 20, 64)       0
 2D)

 dropout_1 (Dropout)         (None, 20, 20, 64)        0

 flatten_1 (Flatten)         (None, 25600)             0

 dense_1 (Dense)             (None, 128)               3276928

 dense_2 (Dense)             (None, 2)                 258

=================================================================
Total params: 3,300,770
Trainable params: 3,300,770
Non-trainable params: 0
_________________________________________________________________
```

# Credits:

## Johann Pineda:

[theonejohann - Overview](https://github.com/theonejohann)

[Johann Pineda - Cinco Ranch High School - Greater Houston | LinkedIn](https://www.linkedin.com/in/johann-pineda-97992a235/)