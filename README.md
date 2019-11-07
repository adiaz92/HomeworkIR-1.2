# HomeworkIR-1.2

Test of cmake commands with a webcam_capture program from beta_robots

##


We do the Fork of the webcam_capture repository from beta_robots usser and clone it in our computer.
```
git clone https://github.com/adiaz92/webcam_capture.git
Clonando en 'webcam_capture'...
remote: Enumerating objects: 62, done.
remote: Total 62 (delta 0), reused 0 (delta 0), pack-reused 62
Desempaquetando objetos: 100% (62/62), listo.
```
We make a build directory in our computer and change to that directory.
```
~$ cd webcam_capture/
~/webcam_capture$ mkdir build
~/webcam_capture$ cd build
```
Then we can build and execute the program with de "cmake" command.
```
~/webcam_capture/build$ cmake ..
-- The C compiler identification is GNU 7.4.0
-- The CXX compiler identification is GNU 7.4.0
-- Check for working C compiler: /usr/bin/cc
-- Check for working C compiler: /usr/bin/cc -- works
-- Detecting C compiler ABI info
-- Detecting C compiler ABI info - done
-- Detecting C compile features
-- Detecting C compile features - done
-- Check for working CXX compiler: /usr/bin/c++
-- Check for working CXX compiler: /usr/bin/c++ -- works
-- Detecting CXX compiler ABI info
-- Detecting CXX compiler ABI info - done
-- Detecting CXX compile features
-- Detecting CXX compile features - done
-- Found OpenCV: /usr (found version "3.2.0") 
-- Configuring done
-- Generating done
-- Build files have been written to: /home/shaenar/webcam_capture/build
```
And execute "make" command to construct the executable.
```
~/webcam_capture/build$ make
Scanning dependencies of target webcam_capture
[ 50%] Building CXX object CMakeFiles/webcam_capture.dir/src/webcam_capture.cpp.o
[100%] Linking CXX executable webcam_capture
[100%] Built target webcam_capture
```
The last step is to execute the program.
```
./webcam_capture 
Opening video device 0
```
![Capture of webcam_capture program](https://github.com/adiaz92/HomeworkIR-1.2/blob/master/media/Captura%20de%20pantalla%20de%202019-11-07%2019-52-34.png)
