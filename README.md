# n_finger_classifier
CNN model made in tensorflow to classify the number of fingers in the image passed as input.

## Description :
The network in a nutshell :

```python

CONV2D -> RELU -> MAXPOOL -> CONV2D -> RELU -> MAXPOOL -> FLATTEN -> FC_LAYER

```

## Output

You can check the predicted output for any image in the test_set or train_set by passing the datasets alingwith their labels into the predefined function "verify(index, dataset, labels)".

![jjjj](https://user-images.githubusercontent.com/38986305/46284685-69776a00-c596-11e8-81ce-71d96c3cdc5e.JPG)
