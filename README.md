# ARKs-confirm-ticket-to-entry
Code for the set of tasks provided by ARK and relevant documentation.

Task 2.2 : Stereo image based collision avoidance

  1. template_matching.py - Code for template matching using cv.TM_SQDIFF.
  2. depth_map_generator.py - Code for generating a qualitative depth map using stereoBM_create.

Task 3.1 : Detection and pose estimation

  1. detect_aruco_images.py and detect_aruco_video.py - Code for detection of aruco tags in images and video respectively by specifiying the appropriate dictionary type. The command for running is :-  
  **For inference on images**   
`python detect_aruco_images.py --image Images/test_image_1.png --type DICT_6X6_100`  
  **For inference using webcam feed**  
`python detect_aruco_video.py --type DICT_6X6_100 --camera True ` 

  2. pose_estimation.py - Code for pose estimation of aruco tags in images and live video feed.
  The command for running is :-  
`python pose_estimation.py --K_Matrix calibration_matrix.npy --D_Coeff distortion_coefficients.npy --type DICT_6X6_100`  

