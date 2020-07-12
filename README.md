# Image-Forensic-Challenge

The challenge comprises several original images captured from different digital cameras with various scenes either indoor or outdoor. The images are divided into images wich we call "pristine" or "never manipulated" and images we call "forged" or "fakes". The "forged" images comprise a set of different manipulation techniques such as copy/pasting and splicing with different degrees of photorealism as we describe below.

All the pristine and fake images are divided into a training and a testing set. In the training set the images will be provided along with its corresponding class and mask. In the testing set the images will be provided without any class or mask.

# Image Forgery Detection
Image Forgery Detection is a Classification problem. Given the image data, the challenge here is to discriminate whether a given image is pristine or fake.


# Image Forgery Localization
Image Forgery Localization attempts to detect accurate tampered areas. Given images and their corresponding ground truths, we need to conduct pixel-level analysis to locate tampered areas.

Example: 

![Output text](https://github.com/gurram1223/Image-Forensics/blob/master/Image%20Forensic%20output.PNG)
