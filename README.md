An OpenCV Project -
Project name: " Hand Gesture"

Steps for this program -
1- Importing necessary libraries cv2, NumPy and math

2-Now we apply gaussian blur to smoothing the image (it removes noise from image) and convert it into BGR ->HSV Image(Huge saturation value)

3-Now we use the morphological technique so that our image our feed won't lose the information.

5- We use dilate and erode morphological (as they are used to filter out the background noise) and apply the threshold to filtered images.

6- Now we will try to find the contours (as it is used for colour and shape analysis)we will find the maximum area of contour by using the function "max", "cv2.contourArea

7- Afterwards we use convex hull well its do the same thing in two different formats.

8- Now we will detect the fingertips by count_defect its not an inbuilt function but what is do is when we will apply the hand it will detect our hand

9- At last it will display the number like if count_defects ==0 it shows 1 and so on...



HOW OUTPUT LOOKS LIKE -

# 1-

![project 1](https://user-images.githubusercontent.com/55251741/98218191-7c2cac00-1f71-11eb-9b31-908f2c282eb1.png)

# 2-
![project 2](https://user-images.githubusercontent.com/55251741/98218520-d9c0f880-1f71-11eb-95a3-2175eb2a91ed.png)

# 3-
![project 4](https://user-images.githubusercontent.com/55251741/98218588-efceb900-1f71-11eb-9dae-d2b2fc86a707.png)

NOTE: There should not be anything in background or else it will detect background cosine values too..




