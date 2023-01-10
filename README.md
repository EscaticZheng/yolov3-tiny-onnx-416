# yolov3-tiny-onnx-416
convert darknet to onnx with fixed pads.
It means conv and maxpool with no auto_pads but fixed pads for model deploy.
# Usage
1. download model weights from https://pjreddie.com/media/files/yolov3-tiny.weights.
2. put yolo_to_onnx.py, weights, cfg in the same directory.
3. run $python yolo_to_onnx.py --model=yolov3-tiny-416
4. if you want to test it, run $python img_predict.py
# Reference
1. https://github.com/jkjung-avt/tensorrt_demos/tree/master/yolo
2. https://github.com/htshinichi/onnx-yolov3
