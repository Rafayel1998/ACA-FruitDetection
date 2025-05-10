# FruitDetection

## Fruits and vegetables predictor

### Getting started

**Create conda environment by running**

```
conda env create
```

**Activate the environment by running:**

```
conda activate fruits
```

**Download the dataset from [here](https://github.com/fruits-360/fruits-360-original-size#).**
**Unzip the dataset and place it in the same directory as this repo.**

**Merge different varieties of the same fruit into one class by running:**

```
python preprocessing/fruit_merger.py
```

**Preprocess the data by running:**

```
python preprocessing/fruit_processor.py
```

### Training the model

**Train the model by running:**

```
python training/fruit_train.py
```
