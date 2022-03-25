# bee-detection
Repository for sharing of pre-trained yolov5 weights for honey bee detection. Trained on the following roboflow dataset: https://app.roboflow.com/matt-nudi/honey-bee-detection-model-zgjnb/overview


Current Training Results based on latest "best.pt" weights file on the above dataset:

|Class|Images|Labels|P|R|mAP@.5|mAP@.5:.95
|---------|------|------|------|------|------|------|
|all|162|1264|0.933|0.642|0.736|0.503|
|bee|162|1144|0.947|0.708|0.871|0.509|
|drone|162|12|1|0.583|0.627|0.464|
|pollenbee|162|105|0.92|0.61|0.78|0.542|
|queen|162|3|0.863|0.667|0.665|0.499|

