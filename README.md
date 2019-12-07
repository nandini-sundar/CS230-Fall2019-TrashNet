
## Directory structure
```
├── TrashNet
│   ├── Split
│   │   ├── test_set
│   │   ├── train_set
│   │   └── val_set
│   ├── annotations
│   │   ├── voc_xmls
│   │   ├── yolo_labels
│   │   ├── label_map.pbtxt
│   │   ├── test.record
│   │   ├── test_labels.csv
│   │   ├── train.record
│   │   ├── train_labels.csv
│   │   ├── val.record
│   │   ├── val_labels.csv        
|   ├── classes.txt
│   └── images

```

# Description

This folder has images cleaning up the original TrashNet dataset (https://github.com/garythung/trashnet) -
image with objects named as plastic actually belonged to trash and a few images that were named as glass/plastic belonged to metal class. 

Bounding boxes for each image was manully annotated using the following annotation tool https://github.com/ManivannanMurugavel/Yolo-Annotation-Tool-New-

Split has the Train-Val-Test split of 80-10-10
Annotations has the bounding box annotations for classes for each image in VOC format, YOLO format and TF Records format