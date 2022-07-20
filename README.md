# A torch version reimplement of Diverse Learner: Exploring Diverse Supervision for Semi-supervised Object Detection

### Training

train 1% data on 4 GPUS:

`bash tools/dist_train_partially.sh semi 1 1 4`

### Testing

#### coco:

| model     | mAP   |
| --------- | ----- |
| 1% data   | 23.72 |
| 5% data   | 31.92 |
| 10% data  | 34.61 |
| 100% data | 44.86 |
