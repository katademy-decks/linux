<details>
	<summary>
		named pipes are FIFO files creatable with mkfifo which allow communication between two _____ on the same host. Network sockets / local domain sockets have mostly superseded them.
	</summary>
		processes
</details>

<details>
	<summary>
		Can processes communicate via sockets? _____
	</summary>
		Yes
</details>

<details>
	<summary>
		The command _____ show process status
	</summary>
		ps
</details>

<details>
	<summary>
		The command _____ sends a job to the foreground
	</summary>
		fg
</details>

<details>
	<summary>
		The directory _____ predominantly stores Processes. The directory is a psuedo-filesystem, dynamically created whenever it is accessed
	</summary>
		/proc
</details>

<details>
	<summary>
		init (or systemd) is the process with PID _____ that executes system startup scripts.
	</summary>
		1
</details>

<details>
	<summary>
		The file /proc/[pid]/stat contains _____
	</summary>
		the process's status information (decoded by the ps command)
</details>

<details>
	<summary>
		Each process has one or several execution contexts called _____, each with its own stack and CPU context, but the exact same address space as their process
	</summary>
		threads
</details>

<details>
	<summary>
		When you run the command ls: 1. Your input gets read by the shell via getline(). 2. The name is found within your $PATH directories. 3. The clone() _____ duplicates the process, giving the child a new PID. 4. The execve() _____ stops the child and replaces its memory stack with data from the ls binary. 5. The parent process runs wait(), as it will clean after the child process when finished
	</summary>
		syscall
</details>

<details>
	<summary>
		The command _____ shows processes of all users
	</summary>
		ps -a
</details>

<details>
	<summary>
		A process's _____ determinates how much CPU time it receives
	</summary>
		scheduling priority
</details>

<details>
	<summary>
		"When a process is cloned, we call the original process the ""_____"", and we call the clone the ""child"""
	</summary>
		parent
</details>

<details>
	<summary>
		The file _____ contains the process's command it's executing
	</summary>
		/proc/[pid]/cmd
</details>

<details>
	<summary>
		The command _____ shows processes along with their user/owner
	</summary>
		ps -u
</details>

<details>
	<summary>
		All other processes are directly or indirectly the children of _____
	</summary>
		The PID 1 process (init or systemd)
</details>

<details>
	<summary>
		The command ps -x _____
	</summary>
		shows procceses unattached to any terminal
</details>

<details>
	<summary>
		Cron's asterisk (* * * * *) syntax denotes, in order: minute, hour, _____, weekday
	</summary>
		day of the month
</details>

<details>
	<summary>
		When you run the command ls: 1. Your input gets read by the shell via getline(). 2. The name is found within your _____. 3. The clone() syscall duplicates the process, giving the child a new PID. 4. The execve() syscall stops the child and replaces its memory stack with data from the ls binary. 5. The parent process runs wait(), as it will clean after the child process when finished
	</summary>
		$PATH directories
</details>

<details>
	<summary>
		The crontab command schedules processes at regular intervals. The cron _____ executes and logs them
	</summary>
		daemon
</details>

<details>
	<summary>
		The command fuser _____
	</summary>
		identifies the process that is accessing a file
</details>

<details>
	<summary>
		The command jobs _____
	</summary>
		lists active jobs
</details>

<details>
	<summary>
		The file _____ contains the process's memory mapping information
	</summary>
		/proc/[pid]/maps
</details>

<details>
	<summary>
		The file _____ contains the process's complete command line
	</summary>
		/proc/[pid]/cmdline
</details>

<details>
	<summary>
		The file /proc/[pid]/cmdline contains _____
	</summary>
		the process's complete command line
</details>

<details>
	<summary>
		Cron's asterisk (* * * * *) syntax denotes, in order: minute, _____, day of the month, weekday
	</summary>
		hour
</details>

<details>
	<summary>
		Cron's asterisk (* * * * *) syntax denotes, in order: minute, hour, day of the month, _____
	</summary>
		weekday
</details>

<details>
	<summary>
		After a clone(), child processes usually run one of the _____ routines, replacing the process they've copied from their parent
	</summary>
		exec()
</details>

<details>
	<summary>
		The command setuid _____
	</summary>
		manipulates a process' UID
</details>

<details>
	<summary>
		The file _____ contains the process's symbolic link to its current directory
	</summary>
		/proc/[pid]/cwd
</details>

<details>
	<summary>
		The file /proc/[pid]/maps contains the process's _____
	</summary>
		memory mapping information
</details>

<details>
	<summary>
		The file /proc/[pid]/statm contains the process's _____
	</summary>
		memory usage info
</details>

<details>
	<summary>
		_____ are programs running indefinitely in the background
	</summary>
		daemons
</details>

<details>
	<summary>
		A process consists of an address space and a set of data structures in the _____
	</summary>
		kernel
</details>

<details>
	<summary>
		The command _____ prints the process tree of a process
	</summary>
		pstree -p [PID]
</details>

<details>
	<summary>
		Are PID's (process ID's) unique? _____
	</summary>
		Yes
</details>

<details>
	<summary>
		The command setgid _____
	</summary>
		manipulates a process's group
</details>

<details>
	<summary>
		The crontab command _____. The cron daemon executes and logs them
	</summary>
		schedules processes at regular intervals
</details>

<details>
	<summary>
		The crontab command schedules processes at regular intervals. The _____ daemon executes and logs them
	</summary>
		cron
</details>

<details>
	<summary>
		The command kill (without flags) sends the SIGTERM signal to a process. SIGTERM may not necessarily terminate the process, as this particular signal be either caught, _____ or ignored by the process.
	</summary>
		blocked
</details>

<details>
	<summary>
		When you run the command ls: 1. Your input gets read by the shell via getline(). 2. The name is found within your $PATH directories. 3. The clone() syscall duplicates the process, giving the child a new PID. 4. The _____ syscall stops the child and replaces its memory stack with data from the ls binary. 5. The parent process runs wait(), as it will clean after the child process when finished
	</summary>
		execve()
</details>

<details>
	<summary>
		Each process has one or several execution contexts called threads, each with its own stack and CPU context, but the exact same _____ as their process
	</summary>
		address space
</details>

<details>
	<summary>
		Each process has one or several execution contexts called threads, each with its own stack and _____, but the exact same address space as their process
	</summary>
		CPU context
</details>

<details>
	<summary>
		After a _____, child processes usually run one of the exec() routines, replacing the process they've copied from their parent
	</summary>
		clone()
</details>

<details>
	<summary>
		Before a dead process disappears, its death must be acknowledged by _____, who does so with a call to wait()
	</summary>
		its parent
</details>

<details>
	<summary>
		The file _____ contains the process's environment variables
	</summary>
		/proc/[pid]/environ
</details>

<details>
	<summary>
		The file _____ contains the process's memory usage info
	</summary>
		/proc/[pid]/statm
</details>

<details>
	<summary>
		The command _____ manipulates a process's group
	</summary>
		setgid
</details>

<details>
	<summary>
		A file is being read in a thread. The kernel requests the file's content be delivered into the requesting process's address space. Until it finishes, the thread is considered _____.
	</summary>
		sleeping
</details>

<details>
	<summary>
		Local domain sockets are connections between processes on the same host, creatable with the ______ system call.
	</summary>
		socket
</details>

<details>
	<summary>
		Which Linux syscalls create a new process? _____
	</summary>
		clone() copies an existing process, whose running command is replaced to a desired new command via exec()
</details>

<details>
	<summary>
		The command _____ limits the use of system-wide resources for a user
	</summary>
		ulimit
</details>

<details>
	<summary>
		A process's scheduling priority determinates how much _____ it receives
	</summary>
		CPU time
</details>

<details>
	<summary>
		Can processes communicate via named pipes? _____
	</summary>
		Yes
</details>

<details>
	<summary>
		The file _____ contains the process's status information (decoded by the ps command)
	</summary>
		/proc/[pid]/stat
</details>

<details>
	<summary>
		The file /proc/[pid]/cwd contains the process's _____
	</summary>
		symbolic link to its current directory
</details>

<details>
	<summary>
		The GID is the numeric identificator for a process's _____
	</summary>
		group
</details>

<details>
	<summary>
		"When a process is cloned, we call the original process the ""parent"", and we call the clone the ""_____"""
	</summary>
		child
</details>

<details>
	<summary>
		Can processes communicate via anonymous pipes? _____
	</summary>
		Yes
</details>

<details>
	<summary>
		Cron's _____ syntax denotes, in order: minute, hour, day of the month, weekday
	</summary>
		asterisk (* * * * *)
</details>

<details>
	<summary>
		Before a dead process disappears, its death must be acknowledged by its parent, who does so with a call to _____
	</summary>
		wait()
</details>

<details>
	<summary>
		The command kill (without flags) sends the _____ signal to a process. _____ may not necessarily terminate the process, as this particular signal be either caught, blocked or ignored by the process.
	</summary>
		SIGTERM
</details>

<details>
	<summary>
		The command ps -u _____
	</summary>
		shows processes along with their user/owner
</details>

<details>
	<summary>
		A _____ is the abstraction memory, processor time, I/O management and monitoring for a single running program
	</summary>
		Process
</details>

<details>
	<summary>
		Do threads share the stack and CPU context with their process? _____
	</summary>
		No
</details>

<details>
	<summary>
		When you run the command ls: 1. Your input gets read by the shell via getline(). 2. The name is found within your $PATH directories. 3. The _____ syscall duplicates the process, giving the child a new PID. 4. The execve() syscall stops the child and replaces its memory stack with data from the ls binary. 5. The parent process runs wait(), as it will clean after the child process when finished
	</summary>
		clone()
</details>

<details>
	<summary>
		The file /proc/[pid]/environ contains the process's _____
	</summary>
		environment variables
</details>

<details>
	<summary>
		The file _____ contains the process's symbolic link to its root directory (set via chroot)
	</summary>
		/proc/[pid]/root
</details>

<details>
	<summary>
		The command _____ is the modern version of fork that handles threads
	</summary>
		clone()
</details>

<details>
	<summary>
		A process' _____ is a set of memory pages that the kernel has marked for the procesS to use
	</summary>
		address space
</details>

<details>
	<summary>
		The command pstree -p [PID] _____
	</summary>
		prints the process tree of a process
</details>

<details>
	<summary>
		The command renice _____
	</summary>
		changes the priority of a running process
</details>

<details>
	<summary>
		The command _____ displays processes in a user oriented format
	</summary>
		ps -u
</details>

<details>
	<summary>
		UTS stands for _____ and it gives a container its own hostname and domain name
	</summary>
		Unix Timesharing System
</details>

<details>
	<summary>
		The command ps -a _____
	</summary>
		shows processes of all users
</details>

<details>
	<summary>
		The command _____ changes the priority of a running process
	</summary>
		renice
</details>

<details>
	<summary>
		The command _____ shows a real-time, interactive list of processes
	</summary>
		top
</details>

<details>
	<summary>
		A parent process has died before it could clean up its child processes via a call to _____. What happens to the child processes? The PID 1 process (usually init or systemd) adopts them and calls wait
	</summary>
		wait
</details>

<details>
	<summary>
		The command top _____
	</summary>
		shows a real-time, interactive list of processes
</details>

<details>
	<summary>
		The command _____ (without flags) sends the SIGTERM signal to a process. SIGTERM may not necessarily terminate the process, as this particular signal be either caught, blocked or ignored by the process.
	</summary>
		kill
</details>

<details>
	<summary>
		The command ps _____
	</summary>
		show process status
</details>

<details>
	<summary>
		The _____ directory contains the process's information on open file descriptors
	</summary>
		/proc/[pid]/fdinfo/
</details>

<details>
	<summary>
		The command kill (without flags) sends the _____ signal to a process. _____ may not necessarily terminate the process, as this particular signal be either caught, blocked or ignored by the process.
	</summary>
		SIGTERM
</details>

<details>
	<summary>
		The file /proc/[pid]/root contains the process's _____
	</summary>
		symbolic link to its root directory (set via chroot)
</details>

<details>
	<summary>
		Jobs are identified by their _____ and JID (Job ID)
	</summary>
		PID (Process ID)
</details>

<details>
	<summary>
		The /proc/[pid]/fdinfo/ directory contains the process's _____
	</summary>
		information on open file descriptors
</details>

<details>
	<summary>
		The clone() syscall returns two values. To the parent it returns the PID of the new child. To the child it returns _____. This informs them both of what role they are playing in the forking
	</summary>
		0
</details>

<details>
	<summary>
		The _____ command schedules processes at regular intervals. The cron daemon executes and logs them
	</summary>
		crontab
</details>

<details>
	<summary>
		The higher the niceness of a process, the _____ priority it has.
	</summary>
		lower
</details>

<details>
	<summary>
		Cron's asterisk (* * * * *) syntax denotes, in order: _____, hour, day of the month, weekday
	</summary>
		minute
</details>

<details>
	<summary>
		Can processes communicate via SysV queues? _____
	</summary>
		Yes
</details>

<details>
	<summary>
		daemons are _____
	</summary>
		programs running indefinitely in the background
</details>

<details>
	<summary>
		The command _____ shows procceses unattached to any terminal
	</summary>
		ps -x
</details>

<details>
	<summary>
		The file /proc/exe contains the process's _____
	</summary>
		symbolic link to the executed file
</details>

<details>
	<summary>
		The command _____ inversely sets the priority of a process (the lower the niceness, the higher the priority)
	</summary>
		nice
</details>

<details>
	<summary>
		Can processes communicate via D-Bus? _____
	</summary>
		Yes
</details>

<details>
	<summary>
		The command fg _____
	</summary>
		sends a job to the foreground
</details>

<details>
	<summary>
		The directory /proc predominantly stores Processes. The directory is a psuedo-filesystem, _____
	</summary>
		dynamically created whenever it is accessed
</details>

<details>
	<summary>
		Can processes communicate via SysV semaphores? _____
	</summary>
		Yes
</details>

<details>
	<summary>
		Can processes communicate via SysV shared memory? _____
	</summary>
		Yes
</details>

<details>
	<summary>
		The command ulimit _____
	</summary>
		limits the use of system-wide resources for a user
</details>

<details>
	<summary>
		A process' address space is _____
	</summary>
		a set of memory pages that the kernel has marked for the procesS to use
</details>

<details>
	<summary>
		The file /proc/[pid]/cmd contains _____
	</summary>
		the process's command it's executing
</details>

<details>
	<summary>
		The command _____ manipulates a process' UID
	</summary>
		setuid
</details>

<details>
	<summary>
		A process' _____ is the user identification number (inherited from the parent process) of the user who created it. Usually, only the creator of a process, and the superuser, can manipulate the process.
	</summary>
		UID
</details>

<details>
	<summary>
		named pipes are FIFO files creatable with _____ which allow communication between two processes on the same host. Network sockets / local domain sockets have mostly superseded them.
	</summary>
		mkfifo
</details>

<details>
	<summary>
		A process' _____ contain variables, code, libraries, stacks and kernel-specific information that the process needs to execute
	</summary>
		address space memory pages
</details>

<details>
	<summary>
		When you run the command ls: 1. Your input gets read by the shell via getline(). 2. The name is found within your $PATH directories. 3. The clone() syscall duplicates the process, giving the child a new PID. 4. The execve() syscall stops the child and replaces its memory stack with data from the ls binary. 5. The parent process runs _____, as it will clean after the child process when finished
	</summary>
		wait()
</details>

<details>
	<summary>
		A parent process has died before it could clean up its child processes via a call to wait. What happens to the child processes? _____
	</summary>
		The PID 1 process (usually init or systemd) adopts them and calls wait
</details>

<details>
	<summary>
		The file _____ contains the process's symbolic link to the executed file
	</summary>
		/proc/exe
</details>

<details>
	<summary>
		The clone() syscall returns two values. To the parent it returns _____. To the child it returns 0. This informs them both of what role they are playing in the forking
	</summary>
		the PID of the new child
</details>

<details>
	<summary>
		Can processes communicate via FIFO pipes? _____
	</summary>
		Yes
</details>

<details>
	<summary>
		When you run the command ls: 1. Your input gets read by the shell via getline(). 2. The name is found within your $PATH directories. 3. The clone() _____ duplicates the process, giving the child a new PID. 4. The execve() _____ stops the child and replaces its memory stack with data from the ls binary. 5. The parent process runs wait(), as it will clean after the child process when finished
	</summary>
		syscall
</details>

<details>
	<summary>
		Upon a process's death, does its parent receive a copy of the exit code? _____
	</summary>
		Yes
</details>

<details>
	<summary>
		The _____ of a child process refers to the PID of the process from which it was cloned.
	</summary>
		PPID
</details>

<details>
	<summary>
		The command kill (without flags) sends the SIGTERM signal to a process. SIGTERM may not necessarily terminate the process, as this particular signal be either caught, blocked or _____ by the process.
	</summary>
		ignored
</details>

<details>
	<summary>
		A process's place in the _____ contains its function parameters, local variables, return addresses and temporary data
	</summary>
		stack
</details>

<details>
	<summary>
		the _____ syscall creates a copy of the original process, with a new PID
	</summary>
		clone()
</details>

<details>
	<summary>
		A file is being read in a thread. The kernel requests the file's content be delivered into the requesting process's _____. Until it finishes, the thread is considered sleeping.
	</summary>
		address space
</details>

<details>
	<summary>
		_____ are FIFO files creatable with mkfifo which allow communication between two processes on the same host. Network sockets / local domain sockets have mostly superseded them.
	</summary>
		named pipes
</details>

<details>
	<summary>
		A process consists of an _____ and a set of data structures in the kernel
	</summary>
		address space
</details>

<details>
	<summary>
		When a process completes, it calls the exit routine, notifying the kernel that it is ready to be die, along with an integer _____ indicating the reason why
	</summary>
		exit code
</details>

<details>
	<summary>
		Processes that have finished execution but had not yet been cleaned up by their parent are called _____ processes.
	</summary>
		zombie
</details>

<details>
	<summary>
		The command nice _____
	</summary>
		inversely sets the priority of a process (the lower the niceness, the higher the priority)
</details>

<details>
	<summary>
		The command _____ identifies the process that is accessing a file
	</summary>
		fuser
</details>

<details>
	<summary>
		When a process completes, it calls the _____ routine, notifying the kernel that it is ready to be die, along with an integer exit code indicating the reason why
	</summary>
		exit
</details>

<details>
	<summary>
		The command ps -u _____
	</summary>
		displays processes in a user oriented format
</details>

<details>
	<summary>
		Do threads share the same address space as their process? _____
	</summary>
		Yes
</details>

<details>
	<summary>
		The command kill (without flags) sends the SIGTERM signal to a process. SIGTERM may not necessarily terminate the process, as this particular signal be either _____, blocked or ignored by the process.
	</summary>
		caught
</details>

<details>
	<summary>
		The _____ is the numeric identificator for a process's group
	</summary>
		GID
</details>

<details>
	<summary>
		_____ are a soft limit on containers - the more of them a container has, the more prioritized it is by a scheduler
	</summary>
		CPU shares
</details>

<details>
	<summary>
		The command _____ lists active jobs
	</summary>
		jobs
</details>

<details>
	<summary>
		When you run the command ls: 1. Your input gets read by the shell via _____ 2. The name is found within your $PATH directories. 3. The clone() syscall duplicates the process, giving the child a new PID. 4. The execve() syscall stops the child and replaces its memory stack with data from the ls binary. 5. The parent process runs wait(), as it will clean after the child process when finished
	</summary>
		getline().
</details>

<details>
	<summary>
		Jobs are identified by their PID (Process ID) and _____
	</summary>
		JID (Job ID)
</details>

<details>
	<summary>
		The command clone() _____
	</summary>
		is the modern version of fork that handles threads
</details>

<details>
	<summary>
		"A process is considered """"asleep"""" when _____"""
	</summary>
		All of its threads are asleep (i.e. waiting for the kernel to finish something for them, like reading contents of a file)
</details>

<details>
	<summary>
		The file _____ directory contains the process's links to open file descriptors
	</summary>
		/proc/[pid]/fd/
</details>

<details>
	<summary>
		Each process has one or several execution contexts called threads, each with its own _____ and CPU context, but the exact same address space as their process
	</summary>
		stack
</details>

<details>
	<summary>
		The file /proc/[pid]/fd/ directory contains the process's _____
	</summary>
		links to open file descriptors
</details>

