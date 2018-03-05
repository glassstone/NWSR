# NWSR (Non-local Weighted Sparse Representation)
Before running the code, you need to do the following steps:

1) Download datasets for training and testing from 
    http://people.duke.edu/~sf59/Fang_TMI_2013.htm
2) Create a "datasets" folder and copy the followings two folders in it:
    For synthetic experiments
    Images for Dictionaries and Mapping leraning


Important m files:

load_train_images.m
    training High-SNR High-resolution (HH) images

noise_level_in_HH_training_images.m
    estimate noise standard deviation in the training set 

demo_train_dictionary.m
    learn a dictionary from training HH images
    or show the atoms of a saved dictionary.

demo_NWSR_1xInterp.m
    Denoising experiments

demo_NWSR_2xInterp.m
    Interpolation experiments
