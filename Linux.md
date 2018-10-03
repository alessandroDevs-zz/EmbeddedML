## Linux Setup

mkdir repos
In repos/

```

git clone https://github.com/ARM-software/ML-examples.git

git clone https://github.com/hromi/SMILEsmileD.git

git clone https://github.com/openmv/openmv.git
sudo apt install python-pip

(pip install --upgrade pip -t .)

pip install opencv-python --user

or

pip install opencv-python==3.4.2.17 -t .

sudo apt-get install libfreetype6-dev

sudo apt-get install pkg-config

sudo apt-get install libpng12-dev

pip install imgaug (-t .)

pip install tqdm (-t .)

sudo add-apt-repository ppa:maarten-fonville/protobuf

sudo apt-get update

Install caffe https://gist.github.com/nikitametha/c54e1abecff7ab53896270509da80215

Blog: https://community.arm.com/innovation/b/blog/posts/low-power-deep-learning-on-openmv-cam
