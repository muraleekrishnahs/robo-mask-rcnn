Msc Artificial Intelligence Project - 
Detection and segmentation of robot hands and objects selected for picking
--------------------------------------------------------------------------

The relentless advancement of machine learning in various spectrums of life from discernable technology, multimedia, and healthcare technology to agriculture, supermarkets, and house interior improvements has become the mainstream discussion as well as the area of research in the scientific community. Computer vision, being an inevitable component of artificial intelligence utilizes machine learning and a deep-learning framework. The present level of computer vision assists in detecting and tracking of individual objects (faces, people walking, automobiles) in an unconstrained environment. Object detection and segmentation is the process of accurately identifying and classifying every item visible in the image frame and assigning a class label to each pixel. By performing instance segmentation at the pixel level, we attempt to develop automated object detection in this study. This is performed by picking the 420 images at random and separating them into a training set and a test set. After that, all these photos were labelled using the LabelImg toolbox. Then, using transfer learning with "coco" weights, these images were trained using a mask R-CNN. The proposed Mask RCNN recognizes both robot hands and food objects, marking them with bounding boxes, class labels, and masks. For each identified item, the confidence scores generated by the Mask-RCNN method are shown. Most of the pictures demonstrate that the recognized items have high confidence levels.


