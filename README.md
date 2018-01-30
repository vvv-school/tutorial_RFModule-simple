Tutorial on basic communication in YARP
=======================================

This tutorial will show you YARP support classes for handling command line parameters and writing modules that perform periodic actiities and have a network interface. 

In particular we will use:
- [yarp::os::ResourceFinder](http://www.yarp.it/classyarp_1_1os_1_1ResourceFinder.html)
- [yarp::os::RFModule](http://www.yarp.it/classyarp_1_1os_1_1RFModule.html)



# How to build the tutorial
 - Open a terminal and switch to the folder which contains C++ code (e.g., `tutorial_rfmodule-simple/`)
 - create a build directory
 - compile and build

 ```
 $ cd tutorial_rfmodule-simple
 $ mkdir build
 $ cd build
 $ cmake ../
 $ make
 ```

# How to run the tutorial
- make sure yarp server is running (`yarp where`), if not open a terminal and run it :
```
$ yarpserver --write
```
- open another terminal and switch to the build directory and run the `tutorial_yarp-port`:

```
$ ./tutorial_rfmodule-simple
```


## Tutorial Solution

Note that the solution is provided from within the branch [**`solution`**](https://github.com/vvv-school/tutorial_rfmodule-simple/tree/solution).

# [How to complete the assignment](https://github.com/vvv-school/vvv-school.github.io/blob/master/instructions/how-to-complete-assignments.md)


