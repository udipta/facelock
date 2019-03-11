The code requires:
-OpenCV 3.0+ :

`sudo apt-get install python3-opencv`

-Numpy :

`sudo apt-get install python-numpy`

-pyautogui :
```
pip3 install python3-xlib
sudo apt-get install scrot
sudo apt-get install python3-tk
sudo apt-get install python3-dev
pip3 install pyautogui
```

-dlib :
```
sudo apt-get install libboost-all-dev
git clone https://github.com/davisking/dlib.git
cd dlib
mkdir build; cd build; cmake .. -DDLIB_USE_CUDA=0 -DUSE_AVX_INSTRUCTIONS=1; cmake --build .
cd ..
python3 setup.py install --yes USE_AVX_INSTRUCTIONS --no DLIB_USE_CUDA
```
-face_recognition :

`pip install face_recognition`
