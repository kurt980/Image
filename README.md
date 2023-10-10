# **Animal & Plant Image Classification Projects**

This project is purely the intersection of what I am currently learning in school and what I like to do the most when I am not in school. I am a heavy user of iNaturalist and I like to go for a hike during weekend and look for animals to encounter. I aim to hand-code a sophisticated image classifier for my personal use. I know that there are many image classifiers on the web and even iNaturalist has its own very powerful computer vision model for species classification. I want to build a model that is as accurate as possible in terms of detecting and recognizing wild animals. In addition to the classifier, I also plan to add more functions such as geospatial/temporal analysis to model the appearance of my favorite animals and help me decide when and where I should pay a visit to their habitats. I also plan to create more preprocessing features such as denoising and deforming which I just learned from my CV classes.

![I think this is a bald eagle and some canada geese][def]

## **Data**
The dataset is the iNaturalist dataset which is open sourced here: https://paperswithcode.com/dataset/inaturalist. The mini-version of the dataset I use has 500000 training images, 500000 testing images and 500000 validation images. However, because I am running it on my laptop, I am only using 40000 training data, 10000 validating data and 10000 testing data. The number of categories is about 10000, which means there are limited instances for each category in the training data. I hope to use my school's GPU some time in the future so I can train more data.


## **Model**
The model I currently run is a CNN model. It has a testing accuracy of about 81%, which is not bad considering the lack of training data. As far as I know the best model on the iNaturalist competition is beyond 99%. Way to go!

[def]: 362.jpg