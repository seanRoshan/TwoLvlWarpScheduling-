# README #

Warp scheduling is a vital stage in a GPU’s execution cycle. Since the program counter for all warps differ, the scheduler needs to take into account the number of available resources and ready operands before issuing the instruction to one of the execution units. In recent years, with the rise of GPGPU’s popularity, numerous attempts have been made to improve the scheduling process, such as dynamic warps, more complex scheduling queues and hiding memory access latencies.

In this project, we have used dynamic warps and two-level round robin scheduling. There are still many improvement possibilities in warp scheduling which can positively affect performance and power consumption, and we look forward to exploring them more in the near future.


### Programming Languages ###

* C++


# Collaborators #

* [Shahriyar ValielahiRoshan](http://shahriyar.us)
* [AmirAli Abdolrashidi](http://aabdolrashidi.com)
* [Devashree Tripathy](http://www.cs.ucr.edu/~dtrip003/)


