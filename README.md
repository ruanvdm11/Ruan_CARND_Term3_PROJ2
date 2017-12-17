[//]: # (Image References)
[image1]: https://raw.githubusercontent.com/ruanvdm11/Ruan_CARND_Term3_PROJ2/master/Test_Images/um_000000.png "Test Result 1"
[image2]: https://raw.githubusercontent.com/ruanvdm11/Ruan_CARND_Term3_PROJ2/master/Test_Images/um_000017.png "Test Result 2"
[image3]: https://raw.githubusercontent.com/ruanvdm11/Ruan_CARND_Term3_PROJ2/master/Test_Images/um_000061.png "Test Result 3"
[image4]: https://raw.githubusercontent.com/ruanvdm11/Ruan_CARND_Term3_PROJ2/master/Test_Images/um_000071.png "Test Result 4"
[image5]: https://raw.githubusercontent.com/ruanvdm11/Ruan_CARND_Term3_PROJ2/master/Test_Images/umm_0000095.png "Test Result 5"
[image6]: https://raw.githubusercontent.com/ruanvdm11/Ruan_CARND_Term3_PROJ2/master/Test_Images/Train_CAM.png "Train Data 1"
[image7]: https://raw.githubusercontent.com/ruanvdm11/Ruan_CARND_Term3_PROJ2/master/Test_Images/Train_Class.png "Train Data 2"
[image8]: https://raw.githubusercontent.com/ruanvdm11/Ruan_CARND_Term3_PROJ2/master/Test_Images/Video_Screenshot.png "Video"

# Udacity CARND Term 3 Project 2
## Semantic Segmentation

## Creating the FCN (Fully Convolutional Network)
In this project it was necessary to create an FCN. FCNs are used to classify objects as well as identify the position of of these objects. This is particularly useful in autonomous vehicles because not only can we train a network to detect the driveable portion of the road ( as in this project) but we can also use this to identify pedestrians and other vehicles. However, one of the drawbacks could be processing time.

The data that was use to train is the Kitti Road data set that has a classified dataset as follows. The first image shows an image taken from a camera. The second image shows the drivable portion of the road (pink).
![alt text][image6]
![alt text][image7]

## Examples of Tested Images
The following images show that the FCN has successfully detected the driveable portion of the road.
![alt text][image1]
![alt text][image2]
![alt text][image3]
![alt text][image4]
![alt text][image5]

Here is a video example of how the FCN detects the corrects section of road.

[![alt text][image8]](https://youtu.be/dQpraiVl_ts)

