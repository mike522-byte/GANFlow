# GANFlow: Unsupervised Generative Adversarial Learning of Optical Flow

Optical flow represents an abstract visual feature, and is a way of describing motion at the pixel level. For a given pair of images, the correspondence between related pixels in consecutive frames is represented as optical flow. Optical flow estimation has been the basis for the realization of many downstream tasks such as object detection and tracking, localization and mapping, visual odometry and multi-view depth estimation, etc. 

This project proposes GANFlow, a method that utilizes the Generative Adversarial Network (GAN) in the way of unsupervised method based on the difference between the fake synthesized image and the real image. The goal of the generator is to generate more accurate optical flow to "trick" the discriminator, which does its best to distinguish between real and fake synthesized images. The two modules are alternately trained to achieve adversarial learning, until a state of balance is reached. Experiments on KITTI 2015 and Sintel datasets demonstrate that the proposed method can improve the performance of unsupervised learning of optical flow.

### Challenges
![image](https://github.com/user-attachments/assets/fe06e951-0f74-4a95-aa66-a1b94811ef5d)
-Mode Collapse
