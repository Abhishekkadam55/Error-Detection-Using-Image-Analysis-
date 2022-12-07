Objective: To build a model to detect Mistake in Manufactured part. It will detect Human Mistake in early stage and 
avoid wrong Quality of product reach customer. 

Solution: Create a error detection model in python using computer vision. Imported Structure similarity from 
skimage. matrix which help to find dissimilarity. Reading image cv2.imread then resize the image. Use Structure 
similarity to find differences, separate difference using threshold and grab them by imutils. grab contours then I loop 
over the contour using cv2. Rectangle. It will draw rectangle difference is, that difference is Error in our image
