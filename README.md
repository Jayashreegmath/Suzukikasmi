# Suzukikasmi
The Suzuki-Kasami algorithm is a token-based algorithm for achieving mutual exclusion in distributed systems.  

Name: Jayashree G Math
BITS ID:2017HT12477

This program is implemented using turbo C++ software 

---------------------- 
Project Report 
----------------------- 

This project is required us to develop a Suzuki-Kasami algorithm that is a token-based algorithm for achieving mutual exclusion in distributed systems Suzuki-Kasami is a modification to Ricart–Agrawala algorithm in which a REQUEST and REPLY message are used for attaining the critical section. but in this algorithm they introduced a method in which a seniority vise and also by handing over the critical section to other node by sending a single PRIVILEGE message to other node. So, the node which has the privilege it can use the critical section and if it does not have one it cannot. If a process wants to enter its critical section and it does not have the token, it broadcasts a request message to all other processes in the system. The process that has the token, if it is not currently in a critical section, will then send the token to the requesting process.
