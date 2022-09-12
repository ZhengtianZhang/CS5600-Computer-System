# Homework 1

## Question 1
100%
Because both processes only include CPU instructions, which means they do not issue I/O requests.

## Question 2
It takes 10 clock ticks to complete both processes.

## Question 3
It takes only 6 clock ticks now to complete both processes. Because while Process 0 is waiting for I/Os to be issued, the CPU is idle and Process 1 can run on it.

## Question 4
Since the -S is set to SWITCH_ON_END, Process 1 can not run on CPU while Process 0 is waiting for I/Os to be issued. So it will takes 3 more clock ticks to complete both processes.

## Question 5\
The circumstance will be identical with Question 3. It takes only 6 clock ticks now to complete both processes.

## Question 6
System resources are NOT being effectively utilized. After the first I/O is issued, Process 0 could keep issuing the remaining I/Os while the other processes are running, but instead it waited for the other to finish.

## Question 7
This time Process 0 keeps issuing the remaining I/Os while the other processes are running. This would save the total run time.

## Question 8
Using the flag -I IO_RUN_IMMEDIATE or -I IO_RUN_LATER does not affect the result.
Using the flag -S SWITCH_ON_END makes the total run time longer than using -S SWITCH_ON_IO.