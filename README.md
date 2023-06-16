# Gallery-Management

## Introducton
Be it for sharing, managing or viewing photos of a specific person, it is always helpful if we can group the images that belongs to respective people. In this project I used OpenCV to detect faces from a set of images and save them separatly with reference to the original picture's name, then using face recognition - extracted the face features in 128D vector. Using the extracted features, I grouped the similar faces together using the K Means clustring machine learning algorithm. After which I saved photos that belongs to respective person in separate directory.

##Please find below the complete steps performed to achive the desired result:
1. Read the saved images for which clustring needs to be done
2. Using OpenCV detected the faces in the images
3. Save the faces that are extracted from the images, with names having reference to the original image (will be handy when we need to segregate actual images)
4. Resize the faces to a particular height while maintaining the actual aspect ratio
5. Extract the facial features in the form of 128D vector using face recognition CNN model
6. Using K Means Clustring machine learning algorithm, group the similar faces together
7. Based on the identified clusters, save the images in which respective faces are present in a seperate directory
8. Now we have separate directory for every peron containing all the pictures in which they appear

## Resources
- https://www.thepythoncode.com/article/hog-feature-extraction-in-python
- https://pyimagesearch.com/2018/07/09/face-clustering-with-python/
- https://pyimagesearch.com/2018/06/18/face-recognition-with-opencv-python-and-deep-learning/
- https://www.geeksforgeeks.org/ml-unsupervised-face-clustering-pipeline/

