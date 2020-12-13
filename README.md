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

