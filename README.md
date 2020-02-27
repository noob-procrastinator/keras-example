# keras-example

An example for beginners about how to train a CNN from keras on a private dataset. 
The example includes two jupyter notebooks. One for a pretrained network and one that is trained from scratch.

The examples include switching between architectures, changing model architecture, image augmentation, fine tuning and result visualization.

## Dataset 

There are 16 classes, common data visualizations such as scatterplots, heatmaps and so on.
This is a small but balanced dataset with around 200 images per class

The data is split into 3 folders; train, validation and test, each containing 2049,684 and 683 images respectively.


## Pretrained vs training from scratch

Using pretrained networks can help for small dataset. You take advantage of the features learned on a bigger and more complex dataset and only adjust the values to your case. This has the advantage of using less resources, and getting better results. The chances are you are not going to train a network better thatn a team of specialists so it is also a good starting point for beginners

