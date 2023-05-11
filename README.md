# Opening-and-Closing

## Aim
To implement Opening and Closing using Python and OpenCV.

## Software Required
1. Anaconda - Python 3.7
2. OpenCV
## Algorithm:
### Step 1:
Import the necessary packages.

### Step 2:
Read the image.

### Step 3:
Create the structuring element.

### Step 4:
Use Opening operation.

### Step 5:
Use Closing Operation.

### Step 6:
Display all the output images.

 
## Program:

``` Python
# Developed By   : Sanjay Kumar S S
# Register Number: 212221240048

# Import the necessary packages

import cv2
import matplotlib.pyplot as plt

# Create the structuring element

kernel=cv2.getStructuringElement(cv2.MORPH_CROSS,(11,11))

# Use Opening operation

img1=cv2.morphologyEx(img,cv2.MORPH_OPEN,kernel)
plt.imshow(img1)

# Use Closing Operation

img2=cv2.morphologyEx(img,cv2.MORPH_CLOSE,kernel)
plt.imshow(img2)

```
## Output:

### Display the input Image

<br>

<img src='https://github.com/SanjayKumarAIML/Opening-and-Closing/assets/93427246/11b50614-27cc-40ee-93a1-9316a269bbb1'>
<br>


### Display the result of Opening


<br>
<img src='https://github.com/SanjayKumarAIML/Opening-and-Closing/assets/93427246/375e4fc4-1357-4a84-9818-97cab80e6806'>
<br>


### Display the result of Closing
<br>

<img src='https://github.com/SanjayKumarAIML/Opening-and-Closing/assets/93427246/0fdc6e73-30c0-4837-858c-5d25d1dc4da5'>
<br>

## Result
Thus the Opening and Closing operation is used in the image using python and OpenCV.
