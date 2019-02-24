# Facial-Expression-Recognition
It recognises facial expression using HAAR cascade. 

To run this project directly open capture.py and run it.
```shell
python3 capture.py
```

Upon opening of camera press "Space" 10 times as it will take 10 photos of you to detect your expression.

The images in dataset are only few selected by me from the whole set of fer2013. You can download full dataset from online (nearly 240 MB).
As the dataset increases the accuracy also increases. If you want to keep your image in dataset then first run capture.py and copy image from images folder to the expression folder. Do not directly paste your image taken from camera to dataset as it should be only image of face and that too gray scale, which is done when capture.py is runned and saved in images folder.

This project uses haarcascade to classify different expressions and Fisher face algorithm to detect the face.

To train your own model run:
```shell
python hard_update.py
```
