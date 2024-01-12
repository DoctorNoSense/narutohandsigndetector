# Baseline Model

Initially, we employed SSD ResNet101 V1 for object detection with reduced dimensions (320x320), as outlined in the pipeline config. The loss of the baseline model was increasing instead of going down. Dissatisfied with the result due to the model's inability to learn (which is shown in the picture below), we opted for an alternative model, maintaining a similar approach for our object detection task. We also decided to gather more data so that it can be able to generalize well. 

![Image Alt Text](https://github.com/DoctorNoSense/narutohandsigndetector/blob/main/obj_1.PNG)
