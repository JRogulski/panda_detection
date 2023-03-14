# panda_detection

This project was made using open source implemenatation of YOLOv7.

Data was gathered from 2 sources :

[link](https://www.kaggle.com/datasets/holoong9291/pandaimagedataset)

[link](https://www.kaggle.com/datasets/ashishsaxena2209animal-image-datasetdog-cat-and-panda)

I took almost all images from the first dataset, and around 350 from the second one. 50Images where used as validation. I laballed them using open-source tool labelImg [github](https://github.com/heartexlabs/labelImg). I trained yolov7([github](https://github.com/WongKinYiu/yolov7)) on 40 epochs, and then tested on few random videos.

Example video:
[mp4](https://user-images.githubusercontent.com/106926091/224957525-d62c49b6-c367-462c-bc37-966b15ef68ad.mp4)
