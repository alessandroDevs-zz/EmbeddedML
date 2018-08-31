# EmbeddedML
In workshop/
git clone https://github.com/ARM-software/ML-examples.git
git clone https://github.com/hromi/SMILEsmileD.git
git clone https://github.com/openmv/openmv.git

In run/
pip install --upgrade pip -t .
pip install opencv-python==3.4.2.17 -t .
pip install imgaug -t .
pip install tqdm -t .
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

