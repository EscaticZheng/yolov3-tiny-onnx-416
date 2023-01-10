# yolov3-tiny-onnx-416
convert darknet to onnx with fixed pads.
# Usage
1. download model weights from https://pjreddie.com/media/files/yolov3-tiny.weights.
2. put yolo_to_onnx.py, weights, cfg in the same directory.
3. run $python yolo_to_onnx.py --model=yolov3-tiny-416
4. if you want to test it, run $python img_predict.py
