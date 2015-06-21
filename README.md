1.	What is the Coflow?
Coflow is one kind of Networking Abstraction for Cluster Applications. 
Paper: http://conferences.sigcomm.org/hotnets/2012/papers/hotnets12-final51.pdf
2.	What is the Coflow Client?
I implement Coflow in Linux kernel 4.0
TCP connection is at least a pair. One is client, the other is server.
So if you want to use my implementation, you must need at least one Coflow Client and one Coflow Server.
It is a prototype. I dont merge Client and Server Code together, next version maybe I will do it,
and add one compile option flag.
3.	How to use?
I am sure both Coflow client and Coflow server can run correctly and stably in Linux kernel 4.0.
You also can port code to other Linux Kernel.
Then compile and install your kernel.
4.	How to design Coflow?
Please refer to my Coflow design PPT.
5.	How to see the result?
This prototype goal is to estimate the Coflow Completion Time.
The result record in Coflow server /var/log/kern.log. 

