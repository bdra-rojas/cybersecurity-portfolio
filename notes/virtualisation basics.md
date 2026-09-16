virtualization
solve the problem have a physical server for every website

the ruel of thumb in IT was: "One server = one application"

virtualization introduced a new idea: 

what if multiple applications cloud share the same physical server safely?
There are a layer called hypervision who manages the VMS, allocating resources and ensuring they operate independently on the same physical server. Allows multiples VMs to hare the hardware while
maintaining isolation from each other.
There are more layers/parts for virtualization.

The hypervisor is the software who manages the resources for each lab machine(VM)
The physical server is who enable share multiple apllications

Hypervisor

It's the software thar creates and manages lab machines.
It is a epecial piece of software that:
- Divides a physical computer into multiple virtual ones
- Gives each lab machine its own share of CPU, memory, and storage
- Keeps everything isolated and safe
- Manages the lifycicle of lab machines(start, stop, pause, clone, delete)

Hypervisors have two main types of implementation, each of which is used for specific scenarios
- type 1 hypervisors run directly on the physical hardware, making them fast, efficient, and ideal for servers and professional environments
- type 2 hypervisors run within an existing operating system, making them easier to install and ideal for learning, testing, or smal setups.

The softwares Oracle VirtualBox and VMware Workstation are type 2.

container

Container is a lighwight, solated enviroment thar runs a single application and all the necessarry components to sipport it. A conteiner borrows the core of the existing system by runnig on the kernel.
They start quickly and use fewer resources than a full machines.
container images ==> Is a pre-packed recipe/template used to create containers


  
