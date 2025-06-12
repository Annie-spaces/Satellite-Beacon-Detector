# Satellite-Beacon-Detector
This is a computervision program that extracts beacon signals from waterfall plots published in Satnogs. Working in conjuction with other repos, it removes the manual process of manually extracting the beacon signals' frequency and time. Very useful for updating TLE or constructing a dataset customized for specific satellite. 

Follow this tutorial, you will be able to create your own dataset and your own coputer vision model that's tailored for your target satellite. A small yet accurate amount of labeled data is sufficient to train a decent computer vision model.

The current dataset includes 29 images in training set and 7 images in validation set. Although the images are not a lot, due to the large amount of beacons labelled in each image, the performs is good. Now, please follow the following step to train your program!

Upload the computervision folder to your google drive. Open the following colab note book. 

Set the run time to GPU, for example T4-GPU

Run it line by line (wait till the current line finished running before you run the next line)

