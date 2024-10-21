1. Dedicated
	- A physical server wholly utilised by a single customer.
	- You have to guess your capacity.
	- You'll overpay for an underutilised a server.
	- You can't vertical scale, you need a manual migration
	- Replacing a server is very difficult
	- You are limited by your Host Operating System
	- Multiple apps can result in conflicts in resource sharing
	- You have a guarantee of security, privacy, and full utility of underlying resources.

2. VMs
	- You can run multiple Virtual Machines on one machine.
	- Hypervisor is the software layer that lets you run the VMs.
	- A physical server shared by multiple customers.
	- You are to pay for a fraction of the server.
	- You'll overpay for an underutilised Virtual Machine.
	- You are limited by your Guest Operating System.
	- Multiple apps on a single Virtual Machine can result in conflicts in resource sharing.
	- Easy to export or import images for migration.
	- Easy to Vertical or Horizontally scale.

3. Containers
	- Virtual Machine running multiple containers.
	- Docker Daemon is the name of the software layer that lets you run multiple containers.
	- You can maximise the utilise of the available capacity which is more cost-effectuve
	- Your containers share the same underlying OS so containers are more efficient than multiple VMs.
	- Multiple apps can run side by side without being limited to the same OS requirements and will not cause conflicts during resource sharing.

4. Functions
	- Are managed VMs running managed containers.
	- Known as Serverless Compute.
	- You upload a piece of code, choose the amount of memory and duration.
	- Only responsible for code and data, nothing else.
	- Very cost-effective, only pay for the time code is running, VMs only run when there is code to be executed.
	- Cold Starts is a side-effect of this setup.
