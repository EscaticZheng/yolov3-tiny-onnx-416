# yolov3-tiny-onnx-416
convert darknet to onnx with fixed pads.
It means conv and maxpool with no auto_pads but fixed pads for model deploy.
# environment
onnx >= 1.9.0 (opset_version >=11, default is 12)  
onnxruntime
# Usage
1. download model weights from https://pjreddie.com/media/files/yolov3-tiny.weights.
2. put yolo_to_onnx.py, weights, cfg in the same directory.
3. run $python yolo_to_onnx.py --model=yolov3-tiny-416
4. if you want to test it, run $python img_predict.py  
![image](https://user-images.githubusercontent.com/107376080/211469353-af4cbe8b-9311-4d04-8f27-3810092d8465.png)

# Reference
1. https://github.com/jkjung-avt/tensorrt_demos/tree/master/yolo
2. https://github.com/htshinichi/onnx-yolov3
