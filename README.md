# EstimateFocalLength

Estimate my phone's intrinsic parameters:
Steps 
1-Run the program on two reliable devices and make a cross product to check if the found values fit with the website values. 
2-Find out if my s20 is new or not (if the camera have been altered).

  1/ The pictures I took with my phone and which fited with the program (with a checkboard pattern)
  
  The "s20-"* taken with the Galaxy s20 we want to test
  
  The "j"* taken with a Galaxy J6+
  
  The "red"* taken with a Redmi note 9S
  
Here are the focal lengths from the J6 and the Redmi according to the website https://www.camerafv5.com/ :
![image](https://user-images.githubusercontent.com/79518374/201107251-8b2be5bb-3b56-4d70-8eb8-4f24ad318808.png)

![image](https://user-images.githubusercontent.com/79518374/201107270-d4837531-6b79-4ab3-89a7-3a66d6bf64d7.png)

  Here the data obtained by running the code :
  For the j6+ we have this array :
  ([[357.80035595, 0. , 225.25547277],
   [ 0. , 358.29041232, 167.44395001],
   [ 0., 0., 1.]])

  For the redmi we have :
  ([[335.17237266, 0. , 221.38019114],
    [ 0. , 335.54983619, 98.44057653],
    [ 0.  , 0.  , 1.  ]])
    
  Let’s take the first value of f (fx) and check the informations given by the manufacturer.
![Screenshot from 2022-11-10 14-45-54](https://user-images.githubusercontent.com/79518374/201108061-e40fe713-0c04-43ba-a762-953a3f80f760.png)

  So we can consider that the result are close enough. The estimated focal length is roughly the same as the focal length given by the manufacturer.


  2/ Discover the truth about the s20 :
  Now, we are sure that our program is good enough to estimate focal length. So let’s do the same method as above and check if the focal length of my refurbished s20 has remained unchanged after the repair.
![image](https://user-images.githubusercontent.com/79518374/201108363-a9582c43-8d19-4c46-bd05-70bd907a7673.png)

  With the program we found :
![Screenshot from 2022-11-10 14-48-23](https://user-images.githubusercontent.com/79518374/201108701-d7ea9139-3753-492d-a50f-e402b8f2aa88.png)

So we should say that the camera have been changed, it’s no more the initial camera.
