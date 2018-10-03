## Linux Setup 

#### Prerequisites 

Ubuntu 18.04.1 LTS

-----

mkdir repos
In repos/

```

git clone https://github.com/ARM-software/ML-examples.git

git clone https://github.com/hromi/SMILEsmileD.git

git clone https://github.com/openmv/openmv.git

sudo apt install python-pip

sudo apt-get install libfreetype6-dev

sudo apt-get install pkg-config

sudo apt-get install libpng12-dev

pip install imgaug 

pip install tqdm 

sudo add-apt-repository ppa:maarten-fonville/protobuf

sudo apt-get update

Install caffe https://gist.github.com/nikitametha/c54e1abecff7ab53896270509da80215

Blog: https://community.arm.com/innovation/b/blog/posts/low-power-deep-learning-on-openmv-cam
