# CMPE283-assignment1
Its an individual assignment. All work is done by me: Priti Sharma(014561274)

 Setting Up the Environment 

1. Downloaded the VMware Fusion for mac operating system

2.	Installed Ubuntu 64-bit as the guest operating system.
3.	Configure VMware processor setting for virtualization features enabled.
    ![image 1](./tmp/Picture1.png?raw=true )

4.	Restart the VM.

5.  Open terminal and run command $ cat/proc/cpuinfo | more. 
   ![image 1](./tmp/Picture2.png?raw=true )

6. Check for “VMX”.

   ![image 1](./tmp/Picture3.png?raw=true )
   
   
    Build and run the program.
    
 1.	Copy make and cmpe283-1.c file into a local folder on VM. "cmpe281-1.c" is updated for all the MSR instructions.
 
 2.	Install make and GCC.
 
 3.	Run “sudo make” command.
    
    ![image 1](./tmp/Picture4.png?raw=true )
 
 4. cmpe283-1.ko file gets created in current directory.check with "ls -latr
    
    ![image 1](./tmp/Picture5.png?raw=true )
    
5.	Run below command to run the kernel code.
 
    $sudo insmod ./cmpe283-1.ko 
    
    ![image 1](./tmp/Picture6.png?raw=true )
    
6.	View the logs or messages with command:
    $sudo dmesg
    
    ![image 1](./tmp/Picture7.png?raw=true )
    
    ![image 1](./tmp/Picture8.png?raw=true )
    
    ![image 1](./tmp/Picture9.png?raw=true )
    
    


 
