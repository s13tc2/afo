# aerial floating objects for maritime search and rescue

## Notebook

`nbs` contains a starter notebook for training an object detection model using pytorch


## About Dataset

### Context

AFO dataset is the first free dataset for training machine learning and deep learning models for maritime Search and Rescue applications. It contains aerial-drone videos with 40,000 hand-annotated persons and objects floating in the water, many of small size, which makes them difficult to detect.

### Content

The AFO dataset contains images taken from fifty video clips containing objects floating on the water surface, captured by the various drone-mounted cameras (from 1280x720 to 3840x2160 resolutions), which have been used to create AFO. From these videos, we have extracted and manually annotated 3647 images that contain 39991 objects. These have been then split into three parts: the training (67,4% of objects), the test (19,12% of objects), and the validation set (13,48% of objects). In order to prevent overfitting of the model to the given data, the test set contains selected frames from nine videos that were not used in either the training or validation sets.
