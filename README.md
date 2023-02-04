# Abnormal Behavior Classification
***
1. Resnet50V2 model [code](https://github.com/yeol0129/AbnormalBehavior-Classification/blob/master/main.py), [output](https://github.com/yeol0129/AbnormalBehavior-Classification/blob/master/Resnet_output.out)
2. EfficientNetB0 model [code](https://github.com/yeol0129/AbnormalBehavior-Classification/blob/master/efficient.py), [output](https://github.com/yeol0129/AbnormalBehavior-Classification/blob/master/Efficientnet_output.out)
***
## Data
> * labeled data
> * image data
> ### Labeled Data sample
> ```
  {
    "id": 207~~,
    "file": "video_20782~~.mp4",
    "metadata": {
        "width": 3840,
        "height": 2160,
        "duration": 313.7,
        "fps": 30,
        "frames": 9411,
    },
    "events": [
        {
            "name": "폭행",
            "start_time": 152.9,
            "duration": 4.95
        }
    ],
    "frames": [
        {
            "number": 4582,
            "image": "frame_4582복2.jpg",
            "annotations": [
                {
                    "label": {
                        "x": 1679,
                        "y": 938,
                        "width": 246,
                        "height": 760
                    },
                    "category": {
                        "code": "theft", ~~~
> ```
