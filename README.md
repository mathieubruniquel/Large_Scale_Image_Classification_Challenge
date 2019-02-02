# Large_Scale_Image_Classification_Challenge
Large Scale Image Classification Challenge performed for the course "MDI343 - Machine Learning" of MS Big Data at TelecomParisTech.

This repository contains the code (in a jupyter notebook) of my work on the project mentionned above.

The purpose of this challenge was to predict whether two images were pictures of a same person.

The training dataset was composed of 3.5millions instances and the test set composed of 1 million.

The features available were :
- 8 features related to the first image, corresponding to some of its characteristics
- 8 features related to the second image, corresponding to the same characteristics as the first image
- 8 scores, that measure the similarity of images 1 and 2

The problem to solve was a supervised binary classification problem as a  label was given, taking values :
- 1 if images 1 and 2 are belonging to the same person
- 0 otherwise

