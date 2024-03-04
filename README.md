# PyArduino-StateSpaceMachine
We have completed the first project so now no code will be given to you. If you would like to add code to this repository, submit a pull request please.
Here is the [documentation](https://pyfirmata.readthedocs.io/en/latest/genindex.html).
> Note: [Oxford](https://languages.oup.com/google-dictionary-en/) defines documentation as "the written specification and instructions accompanying a computer program or hardware".
## State Space Machines
When working with a state space machine, we need to know what a state is because we all know what machines are.
![image](https://github.com/FWBHS-Engineering/PyArduino-StateSpaceMachine/assets/39282164/fb792a0e-48bb-4c58-b874-5b68f0f70d4b)

*FRC Docs [link](https://docs.wpilib.org/en/stable/docs/software/advanced-controls/controls-glossary.html#term-state)*

Very basically, State space machines are controlled by what state they are in and the outside inputs with lots of math. One of the first things we need to understand first is the PID Loop. Here is a photo of it:
![image](https://github.com/FWBHS-Engineering/PyArduino-StateSpaceMachine/assets/39282164/71f5bc2c-a0dc-49b6-be85-fb014bbedd21)

Doesn't it look scary. It's not, don't worry. Basically it uses 3 variables that we can tune like a guitar. PID Control loops are based off of error. Watch this video:
[https://www.youtube.com/watch?v=sFqFrmMJ-sg](https://www.youtube.com/watch?v=sFqFrmMJ-sg)

Now watch this video: [PID Tuning](https://www.youtube.com/watch?v=IB1Ir4oCP5k)

Now we understand PID loops, we can start to apply this. Here is an application for PID Controls: https://www.youtube.com/watch?v=wkfEZmsQqiA

Here is some more information to reference: https://docs.wpilib.org/en/stable/docs/software/advanced-controls/introduction/introduction-to-pid.html

Now we can learn about state space machines. We cand use PID functions to change the value of output devices. We can combind them with more external variables to set even more values. Here is more information on that: https://docs.wpilib.org/en/stable/docs/software/advanced-controls/state-space/state-space-intro.html
