#### Object Detection

Dataset: MS COCO

|Method      | Backbone | Input size | FPS | AP(S) | AP(M)   | AP(L) |  MutliScale | Venue    |
|:---        | :---   | :---       |:--- | :---    |:---     |:---   |  :---     | :---     |
|[M2Det](https://github.com/qijiezhao/M2Det)|VGG16|800x800| - | 29.2 | 47.9 | 55.1 |True | AAAI 2019|
|[M2Det](https://github.com/qijiezhao/M2Det)|VGG16|800x800| 11.8 | 22.1 | 46.5 | 50.2 | False | AAAI 2019|
|[M2Det](https://github.com/qijiezhao/M2Det)|VGG16|512x512| - | 28.0 | 47.4 | 52.8 | True | AAAI 2019|
|[M2Det](https://github.com/qijiezhao/M2Det)|VGG16|512x512| 18.0 | 18.4 | 43.4 | 51.2 | False | AAAI 2019|
|[M2Det](https://github.com/qijiezhao/M2Det)|VGG16|320x320| - | 24.4 | 41.5 | 47.6 | True | AAAI 2019|
|[M2Det](https://github.com/qijiezhao/M2Det)|VGG16|320x320| 33.4 | 14.4 | 37.6 | 47.6 | False | AAAI 2019|
|[M2Det](https://github.com/qijiezhao/M2Det)|ResNet101|512x512| - | 29.6 | 49.6 | 54.3 | True | AAAI 2019|
|[M2Det](https://github.com/qijiezhao/M2Det)|ResNet101|512x512| 15.8 | 20.5 | 43.9 | 53.4 | False | AAAI 2019|
|[M2Det](https://github.com/qijiezhao/M2Det)|ResNet101|320x320| - | 25.3 | 42.5 | 48.3 | True | AAAI 2019|
|[M2Det](https://github.com/qijiezhao/M2Det)|ResNet101|320x320| 21.7 | 14.8 | 38.8 | 47.9 | False | AAAI 2019|




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
|[Tiny-SSD](https://arxiv.org/pdf/1802.06488.pdf) | - | 300x300 | - | 2.3 M  | - | 61.3 | CRV-2018|



#### References:
1. https://github.com/ZHANGHeng19931123/awesome-video-object-detection
2. https://github.com/amusi/awesome-object-detection
