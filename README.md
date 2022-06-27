# vision-object-detection


Tools to label images easily: https://dida.do/blog/the-best-labeling-tools-for-computer-vision


CreateML (Apple) requires an special format for data labeling, you can create it using this script:
https://github.com/ESbros/CreateML_Annotations_JSON



Possible training and prediction models:
- Tensorflow
- Tensorflow Lite (for devices)
- Apple CreateML
- Vertex AI (Google Cloud)



If you want to use Object Detection and you train a model from scratch, it will take forever, you can use Transfer Learning to speed up the process and have an smaller dataset:
https://www.tensorflow.org/lite/models/modify/model_maker/object_detection
https://blog.tensorflow.org/2018/07/training-and-serving-realtime-mobile-object-detector-cloud-tpus.html

