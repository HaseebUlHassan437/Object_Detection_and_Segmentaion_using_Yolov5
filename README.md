# Object_Detection_and_Segmentaion_using_Yolov5
A project for detecting and segmenting strawberry diseases using YOLOv5, with instance segmentation on a custom dataset. The dataset is annotated with polygon points for six disease classes.
# Strawberry Disease Detection with YOLOv5
Instance segmentation using YOLOv5 for strawberry disease detection.

### Detect and segment various diseases in strawberry plants using Deep Learning, YOLOv5, and Python.

In this project, I utilized YOLOv5 to perform instance segmentation on a custom dataset of strawberry diseases.

The dataset includes annotations for six classes, although the dataset description mentions seven classes. Only five classes were found in the training folder. The annotations are provided in `.json` files with polygon points for each object and the corresponding class labels.

- The classes are:
  - Angular Leafspot
  - Anthracnose Fruit Rot
  - Blossom Blight
  - Gray Mold
  - Leaf Spot
  - Powdery Mildew Fruit
  - Rust (mentioned but not found in the dataset)

- You can find the dataset and more details on the project [here](#).

## Strawberry Disease Detection in Images

## Installation

- `pip install numpy`
- `pip install opencv-python`
- `pip install torch`

## Dataset Preparation

- The dataset consists of images paired with `.json` files, containing the polygon points and class labels for each disease. The `.json` files are parsed and converted to YOLO format for instance segmentation.

