# final_docker
<img width="644" alt="docker final" src="https://user-images.githubusercontent.com/69519130/233314335-c6f7000c-1483-438f-b306-7f4a3de395bb.png">
<h3>What is the prerequisite for another machine to run your application if you provide it the docker image ?</h3><br/>
To run a Docker container, the machine must have the Docker engine installed.
Additionally, if your application relies on specific ports or network configurations, you would need to ensure that those ports are available on the 
machine and that the network is configured correctly.
Lastly, if your application requires any external dependencies or configuration files, you would need to ensure that those are available on 
the machine or bundled with the Docker image.



<h3>What is the difference between a virtual machine and a docker container ?</h3><br/>
Virtual machines emulate a complete operating system (OS) and run on top of a hypervisor, which is a layer of software 
that allows multiple VMs to run on a single physical machine.
Docker containers, on the other hand, run on top of the host OS and share the kernel with the host system


VMs require a significant amount of system resources since they need to emulate an entire OS, including its own kernel and system libraries. 
Docker containers, on the other hand, require less overhead since they use the host's kernel and share system libraries, making them more lightweight and efficient.
