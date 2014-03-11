CE3
====

ECE_281
=======

Alex Leaf

Moore Test Bench:
![alt text](http://i59.tinypic.com/sgs7jb.jpg)


Mealy Test Bench:
![alt text](http://i57.tinypic.com/j13n2g.jpg)



Questions:

My moore test bench is correct because going through the testbench shows that each time the stop ='0' and the up_down = '1', after the stop changed to '1', the floor changed each time, this is een in the picture of the moore test bench where "stop" has changed a few tiems already, and it is now stopped and at floor 3.

My mealy test bench is correct because looking at the picture, you can see it is currently at floor 3, and the up_down is at '1' and stop = '0' which means the elevator should be moving up and the next floor should be floor 4.  The picture shows this as the next floor being floor 4, so my test bench is correct.  

is reset synchronous or asynchronous? synchronous

if up_down is set to "go up" and stop is set to 
"don't stop" which floor do we want to go to? the next floor
