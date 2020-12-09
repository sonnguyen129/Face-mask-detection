# face-mask-detection
Đây là project nhận diện khuôn mặt đeo khẩu trang sử dụng OpenCV, Deep Learning. Project có tính ứng dụng rất phù hơp trong thời kì dịch Covid19 đang có diễn biến phức tạp trên toàn thế giới
## Libraries

* Python
* OpenCV
* Tensorflow


## Training process
![plot](plot.png) 
## Results
![result](demo/demo_02.png)
![result](demo/demo_03.png)
## Usage
### Step 1:
Clone this repository
### Step 2:
Train model
```
$ python train_mask_detector.py --dataset dataset
```
### Step 3:
Predict with images
```
$ python detect_mask_image.py --image examples/[image-name].png
```
### Step 4:
Predict with real-time video
```
$ python detect_mask_video.py
```
