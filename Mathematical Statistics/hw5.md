## 8.46

![image-20230310202654820](C:\Users\addas\AppData\Roaming\Typora\typora-user-images\image-20230310202654820.png)

![image-20230310202658163](C:\Users\addas\AppData\Roaming\Typora\typora-user-images\image-20230310202658163.png)

(a)  The histogram of the 210 values of $t_i$ is shown below

​       It looks like a Gamma distribution, where the $\alpha$ is very small, so that it leans to the left.

<img src="C:\Users\addas\AppData\Roaming\Typora\typora-user-images\image-20230310202817843.png" alt="image-20230310202817843" style="zoom:80%;" />

(b) 

<img src="C:\Users\addas\AppData\Roaming\Typora\typora-user-images\image-20230310210653310.png" alt="image-20230310210653310" style="zoom:50%;" />

From the program, we have 

![image-20230310204812836](C:\Users\addas\AppData\Roaming\Typora\typora-user-images\image-20230310204812836.png)

![image-20230310204833745](C:\Users\addas\AppData\Roaming\Typora\typora-user-images\image-20230310204833745.png)

(c) 

<img src="C:\Users\addas\AppData\Roaming\Typora\typora-user-images\image-20230310210328625.png" alt="image-20230310210328625" style="zoom:60%;" />

* Therefore, we can use program to find the $\tilde{\alpha}$ that maximizes the log likelihood

    So $\tilde{\alpha} = 1.595$

    ![image-20230310210458265](C:\Users\addas\AppData\Roaming\Typora\typora-user-images\image-20230310210458265.png)

* Then 
    $$
    \tilde{\beta} = \frac{\tilde{\alpha}}{\bar{X}} \approx 2.633
    $$
    ![image-20230310210632727](C:\Users\addas\AppData\Roaming\Typora\typora-user-images\image-20230310210632727.png)



(d) The two gamma densities is plotted on top of the histogram as shown below. 

* It looks somewhat fit to the histogram
* The Gamma distribution from MoM seems more fit than the one from MLE

<img src="C:\Users\addas\AppData\Roaming\Typora\typora-user-images\image-20230310203340895.png" alt="image-20230310203340895" style="zoom:50%;" />