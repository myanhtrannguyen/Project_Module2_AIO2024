# Project_Image_Depth_Estimation
1. Stereo Matching is a significant problem in the field of Computer Vision, with the goal of reconstructing realistic 3D architecture from a pair of 2D images, known as stereo images. Stereo Matching is often applied in Autonomous Driving, Augmented Reality, and other related applications.

2. In this project, you will get acquainted with the Stereo Matching problem by implementing several algorithms to compute the Disparity Map from a given pair of stereo images. With the Disparity Map, we can obtain actual Depth Information. The stereo image pairs used in this project include:
   
- Tsukuba images: Used in Problem 1.
- Aloe: Used in Problems 2, 3, and 4.

3. Problems

3.1. Problem 1:Build a function to compute the disparity map of two input stereo images (left image (L) and right image (R)) using the pixel-wise matching method.

3.2. Problem 2: Build a function to compute the disparity map of two input stereo images (left image (L) and right image (R)) using the window-based matching method.

3.3. Problem 3: When using the disparity map function built in Problem 2 for the image pair Aloe_left_1.png and Aloe_right_2.png with the input parameters disparity_range = 64 and kernel_size = 5 for both cost functions, the disparity map result has somewhat degraded (noisy). Please use the code from Problem 2 to generate the disparity map image with this configuration and explain (using markdown) why this result occurs.

3.4.Problem 4: Based on the window-based matching disparity map function in Problem 2, and considering the windows as vectors, implement Cosine Similarity in calculating the correlation between two pixels in the left and right images to address the issue in Problem 3."
