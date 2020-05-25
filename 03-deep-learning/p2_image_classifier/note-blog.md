# Image classifier

## Downloading and pre-processing data using `TensorFlow` Datasets

TensorFlow Datasets provides a collection of datasets ready to use with TensorFlow.
It makes downloading and preparing data.

```
pip install tfds-nightly
```

This is the the nightly package pointing to **HEAD** of the repo. It doesn't appear to be available through `conda`. Though `tensorflow-datasets` can be obtained from the `conda` library.

Since `oxford_flowers102` defines a standard splits, so we will use that. Otherwise, we would have used the `subplit` feature to divide the data into train, validation, and test.
