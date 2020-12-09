# face-mask-detection
Đây là project nhận diện khuôn mặt đeo khẩu trang sử dụng OpenCV, Deep Learning. Project có tính ứng dụng rất phù hơp trong thời kì dịch Covid19 đang có diễn biến phức tạp trên toàn thế giới
## Libraries

* Python
* OpenCV
* Tensorflow
* Recommend: Ubuntu(OS)

## Results
### No mask
![result1](demo/demo_2.png)
### With mask
![result2](demo/demo_3.png)
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
Predict with real-time video streams
```
$ python detect_mask_video.py
```
