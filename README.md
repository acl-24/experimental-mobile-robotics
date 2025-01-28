# CMPUT 503 Experimental Mobile Robotics

---

## Exercise 1

This is the repository for CMPUT 503 Exercise 1, where lab_exercises is the package we created under packages. The exercise_1_script.py is under the lab_exercises package. This is the python program to run on the duckiebot to print a hello message.
 
### How to use it

#### 1. building docker image on robot
`dts devel build -f --arch arm32v7 -H MY_ROBOT.local`

#### 2. running program on robot
`docker -H MY_ROBOT.local run -it --rm --net=host duckietown/my-program:latest-arm32v7`


### Collaboration

I collaborated with Minh Pham, phamcnm, on completing the code for this exercise.
