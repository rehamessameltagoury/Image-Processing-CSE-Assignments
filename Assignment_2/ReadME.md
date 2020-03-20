# In this assignment :

  ## Dilation :
     Dilation is one of the basic operators in the area of morphology. The basic effect of the operator on a binary image is to gradually        expand the region boundary of the foreground Pixels.
  ## Edge detection :
        ❶ DILATION:
     We can use dilation in edge detection as well as canny filters, First we dilate the image then we subtracte the dilated image from the original image then Apply the median filter to remove salt and pepper noise.
        ❷ Canny Filter: 
        The Canny edge detector is an edge detection operator that uses a multi-stage algorithm to detect a wide range of edges in images.
        
  ## Erosion :
     The basic effect of the erosion operator on a binary image is to erode away the boundaries of regions of foreground pixels. Thus the        areas of the foreground pixel shrink in size and holes within those areas become larger.
  
  ## Opening and closing :
     These are operations that are derived from the fundamental operations of erosion and dilation. The basic effect of an opening is like      erosion in that it tends to remove some of the foreground (bright) pixels from the edges of regions of foreground pixels. The exact        operation is determined by the structural element only. Closing is similar in some ways to dilation, in that it tends to enlarge the        boundaries of the foreground regions in an image.

  ## Hough Transformation:
     The Hough transform is a feature extraction technique used in image analysis, computer vision, and digital image processing.The purpose of the technique is to find imperfect instances of objects within a certain class of shapes by a voting procedure. This voting procedure is carried out in a parameter space, from which object candidates are obtained as local maxima in a so-called accumulator space that is explicitly constructed by the algorithm for computing the Hough transform.
  ## Contours :
      Contours can be explained simply as a curve joining all the continuous points (along the boundary), having same color or intensity. The contours are a useful tool for shape analysis and object detection and recognition.
  
