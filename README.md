# Object detection with Single Shot MultiBox Detector (SSD)

In this project, we will only use 10 images from our new class to retrain the SSD-ResNet-50 object detector. We'll be taking advantage of this pre-trained object detector in order to get good results quickly.

![training1](https://github.com/chrispmaag/ssd_object_detection/blob/main/images/training1.jpg)
![training2](https://github.com/chrispmaag/ssd_object_detection/blob/main/images/training2.jpg)
![training3](https://github.com/chrispmaag/ssd_object_detection/blob/main/images/training3.jpg)

## Scope/Intent
Based on few-shot method from TensorFlow's object detection tutorial Colab. The intent is to better understand how to retrain a limited number of layers in the pre-trained network.

## Built With
- TensorFlow

## Results

After training, we can see our object detector getting good results on the dog images, with a mean intersection over union (IoU) score of 0.95.

![result1](https://github.com/chrispmaag/ssd_object_detection/blob/main/images/result1.jpg)
![result2](https://github.com/chrispmaag/ssd_object_detection/blob/main/images/result2.jpg)
![result3](https://github.com/chrispmaag/ssd_object_detection/blob/main/images/result3.jpg)
![result4](https://github.com/chrispmaag/ssd_object_detection/blob/main/images/result4.jpg)

There is still opportunity to improve this model because we have some images where the model was not confident enough in its predictions to draw the bounding box (detection scores weren't greater than 0.7). 

![result_no_box](https://github.com/chrispmaag/ssd_object_detection/blob/main/images/result_no_box.jpg)

## Contact

- Chris Pontarolo-Maag - [@chrispmaag](https://twitter.com/chrispmaag) - chrispmaag@gmail.com

## License
[MIT](https://choosealicense.com/licenses/mit/