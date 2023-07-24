# TASK_AND_SCHEDULING
Here i am created  two TASKS AND  SCHEDULING by using FreeRTOS to print HELLO WORLD
In this i am used  following functions:
ConfigASSERT- For debugging purpose
xTaskCreate-This task dynamically using HEAP memory
*The required heap memory is not available then we go for TCB(task control block) and private stack
In the task_handler if you take more local variables it consumes more stack then it leads to stack overflow.
1.pre-emptive scheduling 
2.co-operative scheduling 
when creating xtaskcreation it uses malloc() it allocate memory dynamically


