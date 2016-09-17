# EC601HW1

Osborne, Luke and Lu, Qing

Option 2:
OpenCV:  is most popular computer vision library.  You can do very interesting examples with it.  We will be using it in the class.
 https://github.com/opencv/opencv/tree/master/samples/cpp
Pick one of the examples, modify its input and run it."

## To Compile an opencv sample: 
```
cd <SmileDetect:W_directory>
cmake .
make
```

If you get the error "error while loading shared libraries: libopencv_core.so.2.4: cannot open shared object file: No such file or directory", [follow the instructions here to fix](http://stackoverflow.com/questions/12335848/opencv-program-compile-error-libopencv-core-so-2-4-cannot-open-shared-object-f).


> Old compile instructions, worked on linux but above way is better.
> ~~~~
> g++ -ggdb `pkg-config --cflags --libs opencv` facedetect.cpp -o facedetect
> ~~~~


[Team Trello](https://trello.com/b/ySk6dD1J/hw1)



