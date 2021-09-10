Indian Dance Forms Classification using Transfer Learning

Notebook Summary:

Using Transfer learning concept we will be creating CNN model that can identify different Indian Classical Dance forms.

Dataset contains total 8 different dance forms which are: Bharatanatyam, Manipuri, Odissi, Kathakali, Kathak, Sattriya , Kuchipudi , Mohiniyattam.

This notebook uses VGG16 model from keras which has neural network weights gained through Imagenet competition.

Resource Structure: We have two folders 1) Train 2) Test which contains images in .jpg format and for supporting these images we have train.csv which includes image name and its category and test.csv which includes only image names.
