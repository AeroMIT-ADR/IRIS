# IRIS
![Camera+DepthCam](https://user-images.githubusercontent.com/69350191/123507732-b5dd2f00-d688-11eb-8c47-9e8d4513f631.png)

### Problem Statement : To avoid obsticles and scan maximum QR Codes 

### Process :
- Considered a Depth Camera 
- Considered a IRIS Quadcopter from the available xacro files 
- Updated the Xacro with Depth camera
- It is observed in Rviz that it has two topics being published.
     ##### Point cloud data (2)
     ##### Raw image camera 
     
     
 ### Camera Module
 - An additional RGB cam is added which is used to scan QR codes on the given UGV
 - Kinect RGB is used to scan QR codes on the front plane (walls, blocks etc.)
 - Thus, having a optimal solution to scan maximum QR codes.
