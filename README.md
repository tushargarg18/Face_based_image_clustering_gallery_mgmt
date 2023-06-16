# Gallery-Management

## Introducton
It is usually beneficial if we can categorise the images that belong to different people, whether it be for sharing, organising, or seeing photos of a specific person. In this project, I used OpenCV to identify the faces in a collection of photographs, save each one separately while making note of the name of the original image, and then use face recognition to extract the features of the faces into a 128D vector. I used the K Means clustring machine learning algorithm to group the similar faces together based on the retrieved attributes. I then stored the photographs belonging to the appropriate person in a different directory.

## Actions taken to bring about the intended outcome:
1. Read the saved photos for which clustring must be performed.
2. Face detection in the photos was performed using OpenCV.
3. Save the faces that are extracted from the photographs with names that refer to the original image (useful when we need to split up the actual images).
4. Reduce the height of the faces while preserving the actual aspect ratio.
5. Utilise the CNN face recognition model to extract the facial features as a 128D vector.
6. Group similar faces together using the machine learning method K Means Clustering 
7. Based on the found clusters, save the photos containing the corresponding faces in a separate directory.
8. We now have a distinct directory for each person that contains all of the images of that person.

## Resources
- https://www.thepythoncode.com/article/hog-feature-extraction-in-python
- https://pyimagesearch.com/2018/07/09/face-clustering-with-python/
- https://pyimagesearch.com/2018/06/18/face-recognition-with-opencv-python-and-deep-learning/
- https://www.geeksforgeeks.org/ml-unsupervised-face-clustering-pipeline/

