# bashflow
This repository is meant to store a script called Bashflow. The purpose of this program is to allow a user to draw out process diagrams with sub tasks. 

### Example 1
+ Given the following input file:
```
PARENT TASK 1; SUB TASK 1
PARENT TASK 2
PARENT TASK 3
PARENT TASK 4; SUB TASK 4
PARENT TASK 5; SUB TASK 5A|SUB TASK 5B;SUB-SUB TASK 
```
+ The following is created:
![alt text](/assets/bashflow.png "Logo Title Text 1")

### Example 2
+ Given the following input file:
```
PARENT TASK 1; SUB TASK 1
PARENT TASK 2; SUB TASK 2
PARENT TASK 3; SUB TASK 3;SUBSUB TASK 3|SUBSUB TASK 3B
```
+ The following is created:
![alt text](/assets/bashflowexample2.png "Logo Title Text 1")

### Example 3
+ Given the following input file:
```
PARENT TASK 1; SUB TASK 1
PARENT TASK 2; SUB TASK 2
PARENT TASK 3; SUB TASK 3A|SUB TASK 3B;SUBSUB TASK 3A|SUBSUB TASK 3B
```
+ The following is created:
![alt text](/assets/bashflowexample3.png "Logo Title Text 1")

### Example 4
+ Given the following input file:
```
PARENT TASK 1; SUB TASK 1
PARENT TASK 2
PARENT TASK 3; SUB TASK 3A|SUB TASK 3B
PARENT TASK 4
```
+ The following is created:
![alt text](/assets/bashflowexample4.png "Logo Title Text 1")

### Example 5
+ Given the following input file:
```
PARENT TASK 1
PARENT TASK 2
PARENT TASK 3
PARENT TASK 4
PARENT TASK 5
PARENT TASK 6
```
+ The following is created:
![alt text](/assets/bashflowexample5.png "Logo Title Text 1")
