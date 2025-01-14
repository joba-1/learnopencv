# Download Video

Please download input video from [here](https://drive.google.com/file/d/1l-dFUMD4Q9CzCbRuqYp0DIMjdFICJQT0/view?usp=sharing). Please make sure it is present in the directory from which the code is run.

# Run Code 
The code requires OpenCV 3.x. 

## Python 
The code is tested on Python 3 only, but should work with Python 2 with minor modifications. 

```
python3 video_stabilization.py
```

## C++ 
Compile using the following
```
g++ -O3 -std=c++11 `pkg-config --cflags --libs opencv` video_stabilization.cpp -o video_stabilization
```
Run using the following command 
```
./video_stabilization
```
The code can also be compiled using **cmake** as follows:

```
mkdir build
cd build
cmake ..
cmake --build . --config Release
```

The executable file generated can be run using the following command

```
./video_stabilization
```


# AI Courses by OpenCV

Want to become an expert in AI? [AI Courses by OpenCV](https://opencv.org/courses/) is a great place to start. 

<a href="https://opencv.org/courses/">
<p align="center"> 
<img src="https://www.learnopencv.com/wp-content/uploads/2020/04/AI-Courses-By-OpenCV-Github.png">
</p>
</a>
