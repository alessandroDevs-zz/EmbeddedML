## Linux Setup 

### Prerequisites 

Ubuntu 18.04.1 LTS

---

### Setup

```
mkdir repos

cd repos

git clone https://github.com/ARM-software/ML-examples.git

git clone https://github.com/hromi/SMILEsmileD.git

git clone https://github.com/openmv/openmv.git

cd ../

sudo apt install python-pip

sudo apt-get install libfreetype6-dev

sudo apt-get install pkg-config

sudo apt-get install libpng12-dev

pip install imgaug 

pip install tqdm 

```

Install caffe following the following (guide)[https://gist.github.com/nikitametha/c54e1abecff7ab53896270509da80215]  

