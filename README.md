# DLT-Algorithm
DLT (Direct Linear Transform) is a widely used technique for computing the homography matrix in computer vision. Homography refers to a projective transformation that maps one image plane onto another. Homography computation is used in a variety of computer vision applications, such as image stitching, object recognition, and augmented reality.

The DLT algorithm can be used to compute the homography matrix by using a set of correspondences between points in two images. The homography matrix can then be used to transform one image to the plane of the other image.

The DLT algorithm involves the following steps for computing the homography matrix:

1-Correspondence establishment: Correspondences between points in the two images are established.

2-Normalization: The correspondences are normalized to ensure that the homography matrix is not sensitive to changes in scale or rotation.

3-Matrix setup: The correspondences are used to set up a linear system of equations.

4-Solution computation: The linear system is solved using the DLT algorithm to obtain the homography matrix.

5-Denormalization: The homography matrix is denormalized to obtain the correct scale and rotation.



Implement Additionally the normalized DLT version as explained in Zisserman Book Page 109 Algorithm 4.2
