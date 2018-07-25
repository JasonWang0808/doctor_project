# doctor_project

train: https://s3-us-west-1.amazonaws.com/udacity-dlnfd/datasets/skin-cancer/train.zip  
valid: https://s3-us-west-1.amazonaws.com/udacity-dlnfd/datasets/skin-cancer/valid.zip  
test: https://s3-us-west-1.amazonaws.com/udacity-dlnfd/datasets/skin-cancer/test.zip 

git clone https://github.com/machrisaa/tensorflow-vgg.git tensorflow_vgg模型下载


1. 在打乱下标的时候，random并没有真正随机打乱，因此最好采用机器学习的方法进行打乱
2. 将单热点变为固定的下标，，并将下标归一化成为0-1之间的数字，后期用softmax进行处理
