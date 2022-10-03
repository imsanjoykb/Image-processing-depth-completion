# Image Processing for Depth Completion
This repository provides an implementation Image Processing by Fast Depth Completion

NumPy, OpenCV, Depth Completion are used to implement the approach.

Overview: 

 The proposed algorithm is simple and fast, runs on the CPU, and relies only on basic image processing operations to perform depth completion of sparse LIDAR depth data. Evaluate our algorithm on the challenging KITTI depth completion benchmark, and at the time of submission, our method ranks first on the KITTI test server among all published methods. Furthermore, our algorithm is data independent, requiring no training data to perform the task at hand.
     
##
![Final Output](https://github.com/imsanjoykb/Image-processing-depth-completion/blob/master/assets/final-image/final-image-4.png)
 
# Setup
- Clone the repository with following command :
```
git clone https://github.com/imsanjoykb/Image-processing-depth-completion.git

cd Image-processing-depth-completion
pip3 install -r requirements.txt
```
- Download dataset from below :
```
http://www.cvlibs.net/download.php?file=data_depth_selection.zip
```
- Extract downloaded file and copy contents of "Kitti\depth\depth_selection\val_selection_cropped " directory to the "dataset\kitti_validation_cropped"
- Run main.py

