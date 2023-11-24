# SchedulingAlgorithm
This is a C program that simulates a CPU scheduler. This scheduler is capable of using varied scheduling algorithms such fcfs, rr, nsjf, and psjf to schedule a group of computation tasks.

Program Overview:
----------------------------------------------------------------------------------
 FCFS schedules tasks in the order in which they arrive at the ready queue.

 Computation tasks are served in a round-robin fashion. When there are multiple tasks to be served, 
 each task is executed for a time quantum, then the next task in the queue will be executed. 
 When there is only one task to be served in the computer system, this single task will keep using CPU.

 NSJF schedules tasks in order of the length of the tasks' next CPU burst. No task could be preempted.

 NSJF schedules tasks in order of the length of the tasks' next CPU burst. When a new task arrives, 
 if the next CPU burst of the new task is shorter than what is left of the currently-executing task, 
 PSJF will preempt the currently executing task.
