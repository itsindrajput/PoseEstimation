# Human Pose Estimation
The Aim of this project is to deliver the basic use cases of the Pose Net model for real-time human pose estimation using a webcam feed as the data. 

Pose estimation refers to computer vision techniques that detect human figures in images and video, so that one could determine, for example, where someone’s elbow shows up in an image. To be clear, this technology is not recognizing who is in an image — there is no personal identifiable information associated to pose detection. The algorithm is simply estimating where key body joints are.

#Single-person Pose Estimation
The single-pose estimation algorithm is the simpler and faster of the two. Its ideal use case is for when there is only one person centered in an input image or video. The disadvantage is that if there are multiple persons in an image, keypoints from both persons will likely be estimated as being part of the same single pose.

#Multi-person Pose Estimation
The multi-person pose estimation algorithm can estimate many poses/persons in an image. It is more complex and slightly slower than the single-pose algorithm, but it has the advantage that if multiple people appear in a picture, their detected keypoints are less likely to be associated with the wrong pose. For that reason, even if the use case is to detect a single person’s pose, this algorithm may be more desirable.

![Human Pose Estimation Home Page](https://user-images.githubusercontent.com/70815899/218476373-b1d94333-62fd-4adb-b0cd-4c819f8f3676.png)
