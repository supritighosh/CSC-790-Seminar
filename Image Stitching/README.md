## Image Stitching

Image stitching with OpenCV panorama consists of following steps:

[I] Detecting keypoints and extracting local invariant descriptors using SIFT from the input images.<br>
[II] Between the input images, the descriptors has to be matched.<br>
[III] To estimate a homography matrix, have to use the RANSAC algorithm to use the matched feature vectors.<br>
[IV] Have to apply a warping transformation using the homography matrix which has been obtained using RANSAC algorithm.

