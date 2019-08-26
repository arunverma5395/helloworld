Below are steps for Face Recognition Code configuration
-----------------------------
run feature extraction
pip3 install -r requirements.txt


https://github.com/fchollet/deep-learning-models/releases/download/v0.1/vgg16_weights_tf_dim_ordering_tf_kernels.h5

https://github.com/ageitgey/face_recognition


pyhton3 feature_extractor.py
pyhton3 offline.py
pyhton3 kmeans_color.py
pyhton3 server.py
-----------------------------------------------------------------
Face-->
https://github.com/ageitgey/face_recognition
https://gist.github.com/ageitgey/629d75c1baac34dfa5ca2a1928a7aeaf

sudo apt-get update -> Updates packages (Refreshes Ubuntu Repositories)
git clone https://github.com/davisking/dlib.git

cd dlib
mkdir build; cd build; cmake ..; cmake --build .
update encodings_dir path in server.py
