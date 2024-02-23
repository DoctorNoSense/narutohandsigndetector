# Naruto Dataset Characteristics

- **Source:** Originally from [Kaggle](https://www.kaggle.com/datasets/vikranthkanumuru/naruto-hand-sign-dataset)
- **Issues:** Found unsuitable due to usability and repetitive images
- **Approach:** Privately collected images of three hand signs (Zero, Tiger, Boar) and applied object detection
- **Privacy:** Collected data cannot be disclosed

In total, we collected 80 images for each class using different backgrounds and lighting settings. As a general rule of thumb, 100 pictures per class would work perfectly. The collected images were labeled using [LabelImg](https://github.com/HumanSignal/labelImg), a graphical image annotation tool written in Python that utilizes Qt for its graphical interface. Annotations are saved as XML files in PASCAL VOC format.
The installation guide for LabelImg can be found at this link: [LabelImg Installation Guide](https://github.com/HumanSignal/labelImg)

# Boar

![Image Alt Text](https://github.com/DoctorNoSense/narutohandsigndetector/blob/main/Capture.PNG)

# Tiger

![Image Alt Text](https://github.com/DoctorNoSense/narutohandsigndetector/blob/main/Capture%203.PNG)

# Zero

![Image Alt Text](https://github.com/DoctorNoSense/narutohandsigndetector/blob/main/zero.PNG)


