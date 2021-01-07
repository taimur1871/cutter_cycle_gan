# Cutter Cycle GAN

## Implementation of cycle GAN for cutter image translation

Trying to measure the extent of damage on a tool is tough using conventional image classification / processing techniques.

The idea here is to try and superimpose images from one distribution to a pre-defined shape and try to measure the damage on those.

## Environment & Tools
1. Python 3.8
2. Tensorflow 2.4
3. Numpy 1.19
4. PIL
5. OpenCV
6. Matplotlib 3.2.3

## Challenge

The images below show the challenge of trying to evaluate a cutter. Both images are graded as 3 on the IADC scale. However the damage is very different so it is very tough to generalize this even with very large datasets. To further complicate the issues the orientation of the cutters can vary a lot so there is a need to find features that generalize well and allow clear separation of various categories.
