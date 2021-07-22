<details>
	<summary>
		Do namespaces provide processes with their own view of the system? _____
	</summary>
		Yes
</details>

<details>
	<summary>
		Can namespaces isolate users per process? _____
	</summary>
		Yes
</details>

<details>
	<summary>
		The available namespaces in Linux are, pid, net, _____, uts, ipc, user, time, cgroup
	</summary>
		mnt
</details>

<details>
	<summary>
		Can namespaces isolate networking per process? _____
	</summary>
		Yes
</details>

<details>
	<summary>
		The available namespaces in Linux are, pid, net, mnt, uts, _____, user, time, cgroup
	</summary>
		ipc
</details>

<details>
	<summary>
		Processes within the _____ namespace can only see the other processes within it.
	</summary>
		PID
</details>

<details>
	<summary>
		The available namespaces in Linux are, pid, net, mnt, uts, ipc, user, time, _____
	</summary>
		cgroup
</details>

<details>
	<summary>
		Can network namespaces communicate with each other via a bridge network? _____
	</summary>
		Yes
</details>

<details>
	<summary>
		Does each PID namespace have its own numbering? _____
	</summary>
		Yes
</details>

<details>
	<summary>
		The PID 1 namespace is removed from a PID namespace. What happens? _____
	</summary>
		The PID namespace is destroyed
</details>

<details>
	<summary>
		Using _____ namespaces, you can improve security by giving a unique /tmp or /proc directories to every user.
	</summary>
		mnt
</details>

<details>
	<summary>
		Can namespaces isolate UTS per process? _____
	</summary>
		Yes
</details>

<details>
	<summary>
		The available namespaces in Linux are, pid, _____, mnt, uts, ipc, user, time, cgroup
	</summary>
		net
</details>

<details>
	<summary>
		Can PID namespaces be nested? (namespace within namespace within namespace...) _____
	</summary>
		Yes
</details>

<details>
	<summary>
		Namespaces are created with the _____ syscall.
	</summary>
		clone()
</details>

<details>
	<summary>
		A newly made process inherits its namespaces from the _____ process.
	</summary>
		parent
</details>

<details>
	<summary>
		The available namespaces in Linux are, pid, net, mnt, uts, ipc, _____, time, cgroup
	</summary>
		user
</details>

<details>
	<summary>
		The available namespaces in Linux are, _____, net, mnt, uts, ipc, user, time, cgroup
	</summary>
		pid
</details>

<details>
	<summary>
		Can namespaces isolate Inter-Process Communication per process? _____
	</summary>
		Yes
</details>

<details>
	<summary>
		You can specify the mounted filesystems/devices visible to a process inside a _____ namespace.
	</summary>
		mount namespace
</details>

<details>
	<summary>
		Can process namespaces be used to isolate processes? _____
	</summary>
		Yes
</details>

<details>
	<summary>
		An mnt namespace's mounts be _____ or shared
	</summary>
		private
</details>

<details>
	<summary>
		Can namespaces isolate mounts per process? _____
	</summary>
		Yes
</details>

<details>
	<summary>
		Can namespaces isolate drives and devices per process? _____
	</summary>
		Yes
</details>

<details>
	<summary>
		______ allow processes to use identically named resources and isolate them.
	</summary>
		namespaces
</details>

<details>
	<summary>
		The /proc/[pid]/ns/ directory contains the process's _____
	</summary>
		links to namespaces used by the process
</details>

<details>
	<summary>
		Using the _____ namespaces, processes can be given their own root filesystem (conceptually close to chroot)
	</summary>
		mnt
</details>

<details>
	<summary>
		How many namespaces of can a process simultaneously be in? _____
	</summary>
		One of each type
</details>

<details>
	<summary>
		"When PID namespaces are nested inside one another, a process inside one has as many _____ as the namespace levels it is nested in. This is how features like """"docker in docker"""" can be implemented."""
	</summary>
		PIDs
</details>

<details>
	<summary>
		"Network namespaces can use Virtual Ethernet (veth) pairs to communicate. This involves creating two _____ acting as a """"cross-over cable"""" between them."""
	</summary>
		virtual network interfaces
</details>

<details>
	<summary>
		Can namespaces isolate hostnames per process? _____
	</summary>
		Yes
</details>

<details>
	<summary>
		The available namespaces in Linux are, pid, net, mnt, uts, ipc, user, _____, cgroup
	</summary>
		time
</details>

<details>
	<summary>
		The command setns _____
	</summary>
		adds a process to an existing namespace
</details>

<details>
	<summary>
		The available namespaces in Linux are, pid, net, mnt, _____, ipc, user, time, cgroup
	</summary>
		uts
</details>

<details>
	<summary>
		Can namespaces isolate PIDs per process? _____
	</summary>
		Yes
</details>

<details>
	<summary>
		The command nsenter _____
	</summary>
		enters a Linux namespace
</details>

<details>
	<summary>
		The _____ namespace allows processes to have their own semaphores, message queues and shared memory, without risk of conflict with other processes.
	</summary>
		IPC
</details>

<details>
	<summary>
		Can namespaces isolate resources per one or more processes? _____
	</summary>
		Yes
</details>

<details>
	<summary>
		The _____ namespace allows you to map the UID/GID of processes. Even though you might be a privileged user with UID 0 in a container, you will just be user xxxxx on the host.
	</summary>
		user
</details>

<details>
	<summary>
		An mnt namespace's mounts be private or _____
	</summary>
		shared
</details>

<details>
	<summary>
		The command ip link set dev eth0 netns ns0 _____
	</summary>
		moves a network interface eth0 to namespace ns0
</details>

<details>
	<summary>
		The last process inside a namespace dies. What happens? _____
	</summary>
		The namespace is destroyed. You can prevent this by creating a bind mount inside the namespace.
</details>

<details>
	<summary>
		The _____ namespace allows processes inside one to have their own network stack: sockets, iptables, routing tables and network interfaces (including loopback)
	</summary>
		net
</details>

<details>
	<summary>
		The command _____ moves a network interface eth0 to namespace ns0
	</summary>
		ip link set dev eth0 netns ns0
</details>

<details>
	<summary>
		A process is in a namespace. Which system resources can it see or affect? _____
	</summary>
		Only those allowed in the namespace.
</details>

<details>
	<summary>
		The _____ namespace lets a container mount something, and make it invisible to other containers.
	</summary>
		mnt
</details>

<details>
	<summary>
		The command _____ enters a Linux namespace
	</summary>
		nsenter
</details>

<details>
	<summary>
		The command _____ adds a process to an existing namespace
	</summary>
		setns
</details>

<details>
	<summary>
		The _____ directory contains the process's links to namespaces used by the process
	</summary>
		/proc/[pid]/ns/
</details>

