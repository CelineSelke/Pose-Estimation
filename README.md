# IMPROVING TWO-DIMENSIONAL (2D) HUMAN POSE ESTIMATION USING HISTOGRAM EQUALIZATION
## Dataset 
[2014 COCO Dataset](https://cocodataset.org/#download)
### Required Downloads
- [2014 Training Images](http://images.cocodataset.org/zips/train2014.zip)
- [2014 Training/Validation Annotations](http://images.cocodataset.org/annotations/annotations_trainval2014.zip)

Downloaded contents should be placed in a folder named coco2014 one level above the Pose Estimation directory containing 
- Images in a folder named "images"
- Annotations in a folder named "annotations"

## Required Packages and Libraries 
Pose estimation module using the [MoveNet Lightning Model](https://www.kaggle.com/models/google/movenet/tensorFlow2/singlepose-lightning) (Does Not Require Download, Loaded In Program)
- TensorFlow for manipulation of model's input tensors (pip/conda install tensorflow)
- TensorFlow hub to import model (pip/conda install tensorflow-hub)
- NumPy (pip/conda install numpy)
- OpenCV for image manipulation and processing (pip/conda install opencv-python)
- PyCOCOTools for loading COCO dataset from annotation file and for loading images (pip/conda install pycocotools)
- COCOEval for evaluation of predicted keypoints (pip/conda install cocoeval)
