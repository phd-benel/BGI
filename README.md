# BGI : Broken Glass Insulator Dataset for UAV inspection of power lines

Hy, Peace be upon you,

You will find in this repo a dataset [ images + annotations (Yolov7 format)] which I hope will be useful for your work (view samples from the dataset on figure 1). Especially, if you are interested in detecting anomalies (here broken glass insulators) present on electrical towers by computer vision methods.

![image](https://user-images.githubusercontent.com/82882383/208425768-ed544869-8049-4236-abae-68d34c7be8f0.png)

For this study, we build a database of broken glass insulators from a set of Vietnamese public images [1]. Images were collected during inspections of high voltage power lines by ground patrol agents and helicopters.
Once the images are collected, we clean the images that are not of interest and label the defects on the glass insulators with rectangular bounding boxes on all the images. Accuracy and consistency are checked to ensure that all broken glass insulator cases are labeled in the images and that the labels surround each anomaly. We ensure that the labeling correctly delineates the anomalies to maximize spatial information. We use the Roboflow platform for this work and export the results in Yolov7 annotation format.
Finally, we build a relatively small (~544 images) but diverse dataset that best represents the real deployment environment. More details can be found in Table 1.

![image](https://user-images.githubusercontent.com/82882383/208422024-6d0c3b7d-45ca-4957-8402-9d51efce4a3e.png)

## You can find the broken glass insulator dataset in the release part. 

Reference

[1] hieulc@cpc.vn, “Su110kV_Broken Dataset,” https://universe.roboflow.com/hieulc-cpc-vn/su110kv_broken, Mar. 2022.
