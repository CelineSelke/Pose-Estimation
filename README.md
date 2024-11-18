# IMPROVING TWO-DIMENSIONAL (2D) HUMAN POSE ESTIMATION USING HISTOGRAM EQUALIZATION
## Dataset 
[2014 COCO Dataset](https://cocodataset.org/#download)

Downloaded contents should be placed in a folder named coco2014 one level above the Pose Estimation directory containing 
- Images in a folder named "images"
- Annotations in a folder named "annotations"

## Required Packages and Libraries 
Pose estimation module using the [MoveNet Lightning Model](https://www.kaggle.com/models/google/movenet/tensorFlow2/singlepose-lightning)
- TensorFlow for manipulation of model's input tensors (pip/conda install tensorflow)
- TensorFlow hub to import model (pip/conda install tensorflow-hub)
- NumPy (pip/conda install numpy)
- OpenCV for image manipulation and processing (pip/conda install opencv-python)
- PyCOCOTools for loading COCO dataset from annotation file and for loading images (pip/conda install pycocotools)
- COCOEval for evaluation of predicted keypoints (pip/conda install cocoeval)
