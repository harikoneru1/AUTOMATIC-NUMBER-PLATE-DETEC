AUTOMATIC-NUMBER-PLATE-DETECTION
Description
This is "SSD" Transfer learning based Tensorflow Object Detection model.
It can detect the number plates of vehicle.
For text extraction "EasyOcr" model is used.
Based on the number plates it will give corresponding state (from India) of that vehicle. Can be modified for other countries as well
This is flask based webapp which you can deploy it on pivotal cloud.
For accurate results Image size should be minimum of 800 x 600.
Supported image file formats are ".PNG",".JPG",".JPEG".

python 3.6.9
tensorflow 1.14.0
Tensorflow Object Detection
Faster R-CNN
ssd_inception_v2_coco
flask


to run
$ pip install -r requirements.txt
