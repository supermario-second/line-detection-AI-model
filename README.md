# trend_identify_AI_model
An AI model that can identify data trend
![2025-02-17_12-41-58](https://github.com/user-attachments/assets/a7e10242-4653-437c-856d-79b2442c078c)
# model introduction

this model is used to identify the data line patterns, such as "peak","valley","up","drop"...

from my side, i used this model to detect the anomalies in the data from components of a machine

such as motor torque, cylinder extension time, pump pressure...

this model can detect some trend automatically, with out any data preparations, that means you can give the data as any numbers with different unit

# quick start

1. clone the whole project into your workplace
2. create a new environment in your workplace
3. open the code file deploy_the_model_example.py and run it
4. after running this you will get the information 
5. after loaded the model, it runs as a service, and then you can call it with any request, because it was developed using FastAPI, I also provided the calling example
6. open the test_example, and run it, and you will see the figs from your web browser

::: info
before you can run this, you should install the dependencies

i didn't freeze them, because it just has a little dependencies, i will do this later

:::

::: info
assume that you have a GPU with your computer, but it doesn't meter weather you have or not

if you have, this model will be loaded into GPU memory, less than 1 gb

:::

# concept & and future usage

![image](https://github.com/user-attachments/assets/92f86de3-02fd-45f9-9c15-c4db38951544)


# model structure

![image](https://github.com/user-attachments/assets/228b057a-2bf7-4d9a-9ea6-b25eff4457d1)
