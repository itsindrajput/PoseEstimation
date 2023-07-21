# Human Pose Estimation
Pose estimation refers to computer vision techniques that detect human figures in images and video, so that one could determine, for example, where someone’s elbow shows up in an image. To be clear, this technology is not recognizing who is in an image — there is no personal identifiable information associated to pose detection. The algorithm is simply estimating where key body joints are.

The Aim of this project is to deliver the basic use cases of the Pose Net model for real-time human pose estimation using a webcam feed as the data. PoseNet can be used to estimate either a single pose or multiple poses, meaning there is a version of the algorithm that can detect only one person in an image/video and one version that can detect multiple persons in an image/video. 

- Single-person Pose Estimation
The single-pose estimation algorithm is the simpler and faster of the two. Its ideal use case is for when there is only one person centered in an input image or video. The disadvantage is that if there are multiple persons in an image, keypoints from both persons will likely be estimated as being part of the same single pose.

- Multi-person Pose Estimation
The multi-person pose estimation algorithm can estimate many poses/persons in an image. It is more complex and slightly slower than the single-pose algorithm, but it has the advantage that if multiple people appear in a picture, their detected keypoints are less likely to be associated with the wrong pose. For that reason, even if the use case is to detect a single person’s pose, this algorithm may be more desirable.

# Interactive Human Pose Estimation Showcase
Welcome to our Interactive Human Pose Estimation Showcase! This repository hosts the code and assets used to create our fascinating Human Pose Estimation demo. With this project, we aim to showcase the capabilities of our cutting-edge Pose Estimation model.

## 🎨 Figma Design

Before diving into the code, you can get a glimpse of our beautiful Figma design, which lays the foundation for our interactive demonstration. Explore the design prototype here: 
[Figma Design Prototype](https://www.figma.com/proto/IwBTcGW9T4qGUhQMAbepp8/Human-Pose-Estimation?node-id=210%3A67&scaling=contain&page-id=0%3A1)

## 🚀 Try It Out!

We've deployed our Pose Estimation Website, where you can interactively experience the capabilities of our model. Give it a try by visiting any of the following URLs:
- [poseestimation.netlify.app](https://poseestimation.netlify.app)
- [itsindrajput.github.io/PoseEstimation](https://itsindrajput.github.io/PoseEstimation/)

## 📁 Source Code

Curious about how we brought this amazing demo to life? Look no further! The entire source code for this project is available on GitHub. Feel free to explore, tinker, and contribute to the development of this showcase:
[itsindrajput/PoseEstimation.git](https://github.com/itsindrajput/PoseEstimation.git)


![PoseEstimation HomePage](https://github.com/itsindrajput/PoseEstimation/assets/70815899/fec36c19-04ae-49ae-b8e5-b44886b49c89)
