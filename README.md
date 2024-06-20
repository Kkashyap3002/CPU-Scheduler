# CPU-Scheduler
Author: Kishan Kashyap

Implementation of different scheduling algorithms,here:
1. First Come, First Served (FCFS) scheduling
2. Priority Scheduling scheduling
3. Shortest Job Next (SJF) scheduling
4. Round Robin (RR) scheduling algorithms,

#Instructions for CPU Scheduling:

For FCFS, Preemptive SJF and Priority:
    1. FIRSTLY! Open datagen.cpp and run the program to generate random 
	   number of burst time and arrival time of each process.
	   The values are generated in a text file called datagen.txt.
	   
   2. If you want to do FCFS first, open FCFS.cpp and run the 
	   CPU scheduling for FCFS. The values are outputted in a
	   text file called FCFS_ouput.txt
	  
   3. If you want to do Preemptive SJF first, open SJF.cpp 
	   and run the CPU scheduling for Preemptive SJF. 
	   Since it has 10000 process, you have to wait like 5 mins to complete the run.
	   The values are outputted in a text file called SJF_ouput.txt
	
 4. If you want to do Preemptive Priority first, open Priority.cpp 
	   and run the CPU scheduling for Preemptive Priority.
	   Since it has 10000 process, you have to wait like 5 mins to complete the run.
	   The values are outputted in a text file called Prio_ouput.txt
	   
	  Note: Since it has 10000 process, you have to wait like 5 mins to complete the run
		  for Preemptive SJF and Preemptive Priority.
    

For Round Robin:
  1. FIRSTLY! Open datagenRR.cpp and run the program to generate random 
	   number of burst time and arrival time of each process.
	   The values are generated in a text file called datagenRR.txt.
	   
   Note: Since this algorithm takes a lot of time to process 100-10000 processes (It took hours and even days)
	      We only generate 15 processes (It only took 20-30 seconds.)
		  
  2. Open RoundRobin.cpp and run the CPU scheduling for Round Robin. 
	   The values are outputted in a text file called RR_ouput.txt


The best choice depends on the specific needs of the system and the types of processes running:
For maximizing throughput (number of jobs completed): SJF is ideal, but priority scheduling can be a good alternative.
For minimizing average waiting time: SJF or RR are good options.
For ensuring responsiveness: RR is a strong choice.
For predictable execution: FCFS can work, but may not be efficient.




	   



