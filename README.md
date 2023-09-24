# Dataset-Obsea
In this repository you can find data (images and annotations) about the most abundant fish species recorded in the marine observatory Obsea area during the years 2013 and 2014. In addition, it includes the predictions made with the YOLOv8 model, exactly with the training network "Yolov8x".

The predictions results are not 100% reliable because of the images quality.

Dataset structure:
├── OBSEAv2.v2i.yolov8
│   ├── train
│   │     ├── images
│   │     └── labels
│   │   
│   ├── test
│   │     ├── images
│   │     └── labels
│   │
│   └── valid
│          ├── images
│          └── labels
└── obsea.yaml
