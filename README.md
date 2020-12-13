# Car-Damage-Detection

So, thisproject is of building a model to detect damage in car images.

We will Use Mask-RCNN algorithm for detection.Mask-RCNN is just ans extenstion of Faster RCNN in which it build mask on the detected object.

The most important task is Data Collecting and its annotations.
For this we will need Dataset first.I collected around 1000 images from various sources.

My Data set includes images of scratch, glass damage, dents,or full Damages(mixture of all or badl damaged cars).
Divide the Data into train and Val folder and do the annotations differently.
after saving all these images into a folder now comes the annotation part. For this there is one annotator tool which i used link (https://www.robots.ox.ac.uk/~vgg/software/via/via_demo.html)
annotations should be done in proper manner for batter results. Not to confuse between classes.
After annotating all the images, convert the annotations into JSON file.
I have uploaded the json files of train and val data.

we wil use this Data for our model. So since we know to save our time we use weights of some pre trained model. Here we will use weights pre-trained model of COCO dataset.

I did whole projet on Google colab, since it provides free GPU with good speed.

Environment set-up- This is one of the important steps before training the model on collected images and annotations(labels), as I will use ‘Matterport Mask R-CNN’ repositoryto leverage a few pre-trained CNN n/w weight matrices built on different standard datasets like COCO dataset, ImageNet etc. and custom functions such as, data processing and preparation, configuration setup, model training, creating log-file to save iteration wise weight-matrix objects & n/w losses, object detection, masking detected localized areas etc. To run the custom training function on the images and annotations, we need to first clone the repository.

Now go through the python colab file for the required code and other information.



