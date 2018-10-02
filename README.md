Work in progress...

![new-cam-v4-angle-hero-web](https://user-images.githubusercontent.com/42873333/45641403-543a1000-baad-11e8-82cd-893eab810436.jpg)

![image](https://user-images.githubusercontent.com/42873333/45641345-1e952700-baad-11e8-8d45-bc8b053aa5b2.png)

Smile model: https://github.com/openmv/openmv/blob/master/ml/cmsisnn/models/smile/smile_train_test.prototxt
to get image go to: http://ethereon.github.io/netscope/#/editor

Dropout: https://medium.com/@amarbudhiraja/https-medium-com-amarbudhiraja-learning-less-to-learn-better-dropout-in-deep-machine-learning-74334da4bfc5
Rectified Linear Unit (ReLU): https://www.kaggle.com/dansbecker/rectified-linear-units-relu-in-deep-learning
Inp: Inner product or fully connected layer

-------------------
Setup

# EmbeddedML
In workshop/

git clone https://github.com/ARM-software/ML-examples.git

git clone https://github.com/hromi/SMILEsmileD.git

git clone https://github.com/openmv/openmv.git

In run/

pip install --upgrade pip -t .

-
pip install opencv-python --user

or

pip install opencv-python==3.4.2.17 -t .

-

-

sudo apt-get install libfreetype6-dev

sudo apt-get install pkg-config

sudo apt-get install libpng12-dev

-

pip install imgaug -t .

pip install tqdm -t .

sudo add-apt-repository ppa:maarten-fonville/protobuf

sudo apt-get update

---------
Blog: https://community.arm.com/innovation/b/blog/posts/low-power-deep-learning-on-openmv-cam

---------
# Prepare Dataset

We will be using dataset in "SMILEsmileD/SMILEs/":
- negatives
- positives

check number of images

```
ls SMILEsmileD/SMILEs/negatives/negatives7/. -1 | wc -l
ls SMILEsmileD/SMILEs/positives/positives7/. -1 | wc -l
```

Augment number of images

```

```


------------------------------

Deprecated!!!!

Protobuff install

git clone https://github.com/google/protobuf.git

cd protobuf/

./autogen.sh

./configure

make

make check

sudo make install

sudo ldconfig # refresh shared library cache.

protoc -h
