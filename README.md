# Module 13 Challenge 
### Pete Petersen
### April 20, 2022

In this project we use tensorflow, sklean and keras to buils and optimize several models.  At the end of the project we evaluate the each of the models for their accuracy.

In order to use this project you may clone this repo and install the following dependancies. Some of your results may differ as some time was spent researching and making a local envirionment on an Apple M1 Pro.  For those interested, please follow the directions found on the Apple Tesorflow repo.

[Apple Developer Tensor Metal Repo](https://developer.apple.com/metal/tensorflow-plugin/)

```
import pandas as pd
import tensorflow as tf
from tensorflow.keras.layers import Dense
from tensorflow.keras.models import Sequential
from sklearn.model_selection import train_test_split
from sklearn.preprocessing import StandardScaler,OneHotEncoder
from pathlib import Path
```

