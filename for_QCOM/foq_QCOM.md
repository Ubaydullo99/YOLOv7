## Windows, Yolov7 and 5, for detecting new images code 

    python segment/predict.py --weights {HOME}/yolov7/seg/runs/train-seg/custom/weights/best.pt --conf 0.25 --source ../images

## model predict.py for video

    !python segment/predict.py --weights {HOME}/yolov7/seg/runs/train-seg/custom/weights/best.pt --conf 0.25 --source ../videos
