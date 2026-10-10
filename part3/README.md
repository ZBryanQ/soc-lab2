# Lab 2 Part 3 README

To compile part 3, create the run
```
gcc dot_ref.c test_ref.c -o build/test_ref -lm
```
Then run
```
./test_ref
```
which will report max absolute and relative error for test cases.
In addition, Claude has generously included an option to generate the  text file, if so desired:
```
./test_ref --dump log.txt
```
The log is formatted with the following content, separated by spaces:
Given x dot y:  
```number of blocks | x_scale | qs quantized numbers | y_scale | qs quantized numbers | answer```

You may have to create the build/ folder in /part3 since I am not committing local builds.