#### Object Detection

Dataset: VOC 2007

|Method      | Backbone | Input size | FPS | #Params | FLOPs   | mAP(%)|  Venue    |
|:---        | :---   | :---       |:--- | :---    |:---     |:---   |  :---     |
|[DSOD](https://github.com/szq0214/DSOD) |DS/64-192-48-1| 300x300 | 17.4 | 14.8 M  | 15.07B   | 77.7 | [ICCV 2017](http://openaccess.thecvf.com/content_ICCV_2017/papers/Shen_DSOD_Learning_Deeply_ICCV_2017_paper.pdf) |
|[SSD]() |VGGNet| 300x300 | 46| 26.3 M  | 31.75B   | 77.2 | []() |
|[YOLO-v2]() |Darknet-19| 416×416| 67 | 48.20M | 34.90B | 67.8| []() |
|[YOLO]() |-| 448×448 | 45 | 188.25M  | 40.19B   | 63.4 | []() |
|Faster-RCNN |  VGG  | 600x1000  | 7   | 134.7 M | 188.12B | 73.2  |           | 
|[R-FCN]() |ResNet-50|600×1000| 11 | 31.90M | - | 77.4 | []() |


#### Real Time Object Detection

|Method      | Backbone | Input size | FPS | #Params | FLOPs   | mAP(%)|  Venue    |
|:---        | :---   | :---       |:--- | :---    |:---     |:---   |  :---     |
|[Tiny-DSOD](https://arxiv.org/abs/1807.11013) |G/32-48-64-80| 300x300 | 105 | 0.95 M  | 1.06B   | 72.1  | [BMVC 2018](http://bmvc2018.org/contents/papers/0145.pdf) |
|[Small-DSOD](https://arxiv.org/abs/1807.11013) |DS/64-64-16-1| 300x300 | 27.8 | 5.9 M  | 5.29B   | 73.6  | [ICCV 2017](https://github.com/szq0214/DSOD) |
|[PELEE](https://arxiv.org/pdf/1804.06882.pdf) |  Dense Blocks | 300x300 | - | 5.98 M  | 1.21B   | 70.9  | [NeurIPS 2018]() |
|[Tiny-YOLOv2](https://github.com/simo23/tinyYOLOv2) | - | 416x416 | 207 | 15.12 M  | 6.97B   | 57.1  | [CVPR 2016](https://pjreddie.com/darknet/yolo/)|

