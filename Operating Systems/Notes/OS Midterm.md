# OS: Midterm

## Section 1

![image-20230321123738253](C:\Users\addas\AppData\Roaming\Typora\typora-user-images\image-20230321123738253.png)

* Not necessary
* PID numbers can be reused

![image-20230321124022695](C:\Users\addas\AppData\Roaming\Typora\typora-user-images\image-20230321124022695.png)

* `-O2` is the optimization flag
* faster but harder to debug
    * some instructions may disappear
    * some may be out of order
    * some functions may be gone

![image-20230321124153683](C:\Users\addas\AppData\Roaming\Typora\typora-user-images\image-20230321124153683.png)

* False
* Should be the other way around
    * TRAP goes from user to kernel
* Return from TRAP

## Section 2

![image-20230321124259603](C:\Users\addas\AppData\Roaming\Typora\typora-user-images\image-20230321124259603.png)

* If you copy from one docker container to another docker container, it should run just fine
* This is perfectly possible

![image-20230321124404765](C:\Users\addas\AppData\Roaming\Typora\typora-user-images\image-20230321124404765.png)

* There cannot be a race condition if nobody is writing to the file
    * Nobody is modifying
    * The data is never changed
* Read only => No race condition

![image-20230321124605812](C:\Users\addas\AppData\Roaming\Typora\typora-user-images\image-20230321124605812.png)

* possible
* File is fully buffered
    * before `fork()` nothing is printed
    * after `fork()` it's printed



![image-20230321124836927](C:\Users\addas\AppData\Roaming\Typora\typora-user-images\image-20230321124836927.png)

![image-20230321124945574](C:\Users\addas\AppData\Roaming\Typora\typora-user-images\image-20230321124945574.png)

* You have to use `-g` flag 



![image-20230321125027842](C:\Users\addas\AppData\Roaming\Typora\typora-user-images\image-20230321125027842.png)

* `exit()` never fails
* `SIGTERM` is for interprocess conmmunication
* `exit()` is not implemented based on signals

![image-20230321125139071](C:\Users\addas\AppData\Roaming\Typora\typora-user-images\image-20230321125139071.png)

* Real life scenario of the diner-philosopher problem



## Section 3

![image-20230321125404602](C:\Users\addas\AppData\Roaming\Typora\typora-user-images\image-20230321125404602.png)

## Section 4

![image-20230321125905505](C:\Users\addas\AppData\Roaming\Typora\typora-user-images\image-20230321125905505.png)

* Decrementing the number in child will never affect the parent

## Section 5

![image-20230321130102417](C:\Users\addas\AppData\Roaming\Typora\typora-user-images\image-20230321130102417.png)

## Section 6

![image-20230321130502132](C:\Users\addas\AppData\Roaming\Typora\typora-user-images\image-20230321130502132.png)

* calling wait in child process will fail
    * return -1
* calling wait in parent process will succeed
    * return pid of child

![image-20230321130856197](C:\Users\addas\AppData\Roaming\Typora\typora-user-images\image-20230321130856197.png)

* you can not have 2 values if the first one is 202



## Section 7

![image-20230321130922793](C:\Users\addas\AppData\Roaming\Typora\typora-user-images\image-20230321130922793.png)

## Section 8

![image-20230321132245627](C:\Users\addas\AppData\Roaming\Typora\typora-user-images\image-20230321132245627.png)

![image-20230321132430133](C:\Users\addas\AppData\Roaming\Typora\typora-user-images\image-20230321132430133.png)

* The child runs super fast
* when the parent send SIGINT, the child already printed 0 and terminated