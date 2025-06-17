Original project code(outdated) -> MP_project_attempt_3(CNN).ipynb
2050 project code -> MP_project_attempt_3(CNN 2025 Remastered).ipynb

The original project code was for a Fall 2022 class project at Lamar University. For some reason, it doesn't seem to work properly which is why there is a "2025 Remastered" version in which changes were made with help from online sources to get the project in working order instead of having errors. I'm guessing the error encountered when running the original code likely comes from Tensorflow from 2022 being different compared to today's Tensorflow.

Purpose of project code was to create a CNN that can learn to classify images from a dataset. 
The dataset used is Fashion MNIST which is similar to MNIST, but uses images of clothes instead of numbers.

The code shown in this repository was run on Google Colab. Attempting to run this code somewhere else may not work.

*Summary of the process of running the 2025 version of the project code on Google Colab*
When the code is first running, there are important tools that are imported as well as the fashion_mnist dataset. 
The dataset will be loaded and a sample of the dataset will be shown (labeled images for examples). 
The dataset will be formated and have the to_categorial applied to prepare the data for use in a model.
A model with 3 layers will be setup, compiled, then trained for 10 cycles.
After training is completed, the model will be tested and the results will be shown in a graph and the accuracy printed.
As of doing a few tests runs with the code, the model seems to be atleast 80% accurate when attempting to classify images of clothes from the fashion_mnist dataset.
