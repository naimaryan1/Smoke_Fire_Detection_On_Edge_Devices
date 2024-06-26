# Smoke_Fire_Detection_On_Edge_Devices
Towards Smoke and Fire detection via images using Deep Learning on resource constrained embedded devices. 

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body>

<table>
    <tr>
        <td><img src="read_me_images/fire_1.png" style="width: 75%; height: 75%"></td>
        <td><img src="read_me_images/smoke_1.png" style="width: 75%; height: 75%"></td>
    </tr>
</table>

</body>
</html>

Developer: Ary Naim (anaim@unm.edu)

Advisor: Dr. Marios Pattichis (pattichi@unm.edu)

Deep learning libraries:

1) TensorFlow
2) Keras

INSTRUCTIONS:

1) RECOMMENDED START HERE

For the corresponding Google Collab go to: https://colab.research.google.com/drive/1d6qh1uXNrlptKafsonEZLDvkHJko7wD4?usp=sharing

2) For detailed instructions on using custom data sets for to the PDF doc "Step by Step Guide for YOLOv8 Using Keras With Custom Datasets"

3) If you are uploading custom datesets based on the guide in step you can refer to the code in the zip folder "GeneratorBasedBuilder_my_fire_smoke_dataset".

4) For code only refer to dir "code_only"


References:

1) Implementation was heavily based on:                         https://keras.io/examples/vision/yolov8/
2) Adding custom dataset via tensorflow:                        https://www.tensorflow.org/datasets/add_dataset
3) Dataset                                                      https://github.com/gaiasd/DFireDataset
4) Attemptiong to reproduce this paper however using YOLOv8:    
                                                                https://link.springer.com/article/10.1007/s00521-023-08260-2
                                                                https://www.researchgate.net/publication/361649776_An_automatic_fire_detection_system_based_on_deep_convolutional_neural_networks_for_low-power_resource-constrained_devices#fullTextFileContent
