# Background Matters
 
● *We wrote an algorithm to create an invisibility cloak.Invisibility cloak means we can hide a particular thing in a specific color*
![image](https://user-images.githubusercontent.com/74312429/142825900-08cd948b-a531-407e-9c98-02bdb014d7db.png)

## Learnt About
* *cv2 (Camera vision library)*
* *Saturation and segmentation techniques*
 
## Steps to write an algorithm to create an invisibility cloak.
  * *We imported the cv2 , time and numpy libraries to our file.*
  * *We wrote code and prepared for writing the output video using **videoWriter_fourcc**.*
  * *We started to read the video and warmed up(sleep) the camera*
  * *We wrote code to capture the background in range of 60 and flipped the background.*
  * *We read every frame from the webcam, until the camera is open.*
  * *We coded to convert the color from BGR to HSV for better detection.*
  * *Then we coded to create the masks.*
  * *Then we created an inverted mask to segment out the red color from the frame.*
  * *We then segmented the red color part out of the frame using bitwise and inverted mask.*
  * *We wrote code to create an image showing static background frame pixels only for the masked region.*
  * *We coded to get the video as our output and close all the windows.*

## More About HSV
  * *Converting the color from BGR to HSV.*
  * *HSV - Hue saturation value.*
  * *0-Red,120-green,240-Blue In **HSV**.*
  * *Saturation is the intensity(How much visible).**EX:** Pink is less saturated compared to red.*
