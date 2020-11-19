# Understanding-Clouds-from-Satellite-Images

A Flask-based Web App to segment user-uploaded Satellite Images with different cloud organization patterns and visualized the history cloud patterns statistics.  

Image segmentation algorithm: U-Net with pre-trained backbone ResNet-34, and ResNeXt101 as post-processing
## Objective
<ul>
<li>Shallow clouds is an important indication of Earth’s climate. However, they are difficult to represent in climate models due to various and murky organizations.</li>
<li>Build better models to classify cloud organization patterns. And understand how clouds will shape our future climate.</li>
</ul>

## Main System
<ul>
<li>Python, Spark SQL: preprocess data </li>
<li>GCP compute engine, U-Net: Image Segmentation Model</li>
<li>Flask, Google Data Studio, BigQuery: Interactive  Website</li>
</ul>

![method](https://github.com/lmxs1237/Understanding-Clouds-from-Satellite-Images/blob/master/images/method.png?raw=true)

## Reference
1. [segmentation_models](https://github.com/qubvel/segmentation_models)  
2. [segmentation-in-pytorch-using-convenient-tools](https://www.kaggle.com/artgor/segmentation-in-pytorch-using-convenient-tools)  
3. [satellite-clouds-u-net-with-resnet-encoder](https://www.kaggle.com/xhlulu/satellite-clouds-u-net-with-resnet-encoder)
