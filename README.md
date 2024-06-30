# SJF
Shortest Job First Scheduling Algorithm
Below are the steps to perform the SJF scheduling program in c.

Firstly, we will begin the procedure.
After that, we will Consider the number of elements to be inserted.
Then, we will choose the process with the shortest burst time and will execute the first process.
We will check that if both processes have the same burst time length then the FCFS scheduling algorithm is used.
We will make the average waiting time for the next process.
We will begin with the first process, make the above selection, and place the other processes in a queue.
We will calculate burst time.
We will display the values that are related.
In the end, we will stop the process.
Likewise, we will run all the steps until all the processes are executed.
Characteristics of Shortest Job Scheduling
This algorithm is Greedy.
It is helpful for batch processing.
Shortest Job First has the benefit of having the quickest average waiting time out of all scheduling algorithms.
By offering shorter assignments that must be finished first and often have a quicker turnaround time, enhances job output

Enter the number of process:4
Enter process name, arrival time& burst time:
1
1 
3
Enter process name, arrival time& burst time:
2
2
4
Enter process name, arrival time& burst time:
3
1
2
Enter process name, arrival time& burst time:
4
4
4
Process name	Arrival time	Burst time	Waiting time	Turnaround time
3	1	2	0	2
1	1	3	2	5
2	2	4	4	8
4	4	4	6	10
Average waiting time: 3.000000
Average turnaround time: 6.250000

