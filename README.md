# inception-resnet-v2 based segmentation DNNs

This repository holds definitions for semantic segmentation DNNs based on the [inception-resnet-v2 architecture](https://research.googleblog.com/2016/08/improving-inception-and-image.html).

## code

* [pruned & dilated inception-resnet-v2 (PD-IR2)](https://github.com/MalteOeljeklaus/incept_resnet2_segmentation/tree/master/PD-IR2)

## IoU evaluation on [cityscapes](https://www.cityscapes-dataset.com/)

| Model | runtime | Average | road | sidewalk | building | wall | fence | pole | trafficlight | trafficsign | vegetation | terrain | sky | person | rider | car | truck | bus | train | motorcycle | bicycle |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| PD-IR2 | 0.69s | 67.29 | 97.88 | 81.87 | 90.18 | 39.54 | 47.74 | 54.78 | 58.12 | 69.89 | 91.30 | 70.38 | 94.36 | 76.97 | 51.90 | 92.86 | 40.69 | 54.27 | 55.22 | 45.52 | 65.13 |


## architecture

| pruned & dilated inception-resnet-v2 (PD-IR2) |
| --- |
| ![pruned & dilated inception-resnet-v2 (PD-IR2)](https://github.com/MalteOeljeklaus/incept_resnet2_segmentation/raw/master/doc/PD-IR2.png "pruned & dilated inception-resnet-v2 (PD-IR2)") |
