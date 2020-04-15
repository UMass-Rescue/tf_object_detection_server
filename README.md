# tf_object_detection_server
A server to easily create web services for object detection models created using TensorFlow.

### Usage 

```
serv = TFObjectDetectionServer(path_to_frozen_graph, path_to_pbtxt, 'cat_detector')
serv.run(host='localhost', ip=12222)
```
