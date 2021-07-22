<details>
	<summary>
		the syscalls for files are open(), close(), read() and _____
	</summary>
		write()
</details>

<details>
	<summary>
		the _____ syscall adds a directory entry (hard link?)
	</summary>
		link
</details>

<details>
	<summary>
		the syscall _____ opens/creates a file and returns a file descriptor
	</summary>
		open
</details>

<details>
	<summary>
		The command _____ traces signals and system calls
	</summary>
		strace
</details>

<details>
	<summary>
		the syscalls for files are open(), close(), _____ and write()
	</summary>
		read()
</details>

<details>
	<summary>
		the syscalls for files are open(), _____, read() and write()
	</summary>
		close()
</details>

<details>
	<summary>
		A signal's _____ must perform a default action, invoke a handler function, block, or ignore it.
	</summary>
		receiving process
</details>

<details>
	<summary>
		The kernel code and function stubs used by each process are stored within _____
	</summary>
		The address space pages of each process
</details>

<details>
	<summary>
		each process has 3 user IDs: _____ effective ID (determines privileges) saved ID (set by exec to match the effective ID)
	</summary>
		real ID (the owning user)
</details>

<details>
	<summary>
		the _____ syscall makes a symbolic link
	</summary>
		symlink
</details>

<details>
	<summary>
		the syscall _____ releases a file descriptor
	</summary>
		close
</details>

<details>
	<summary>
		each process has 3 user IDs: real ID (the owning user) effective ID (determines privileges) _____
	</summary>
		saved ID (set by exec to match the effective ID)
</details>

<details>
	<summary>
		_____ gets/sets default permissions for new files/directories created henceforth by a process.
	</summary>
		umask
</details>

<details>
	<summary>
		Signals can either be sent by the kernel or _____
	</summary>
		the kill syscall
</details>

<details>
	<summary>
		How many users can a file or directory be owned by at most? _____
	</summary>
		One
</details>

<details>
	<summary>
		Can exec can change IDs of files via setuid? _____
	</summary>
		Yes
</details>

<details>
	<summary>
		the file permission classes are _____, group, other
	</summary>
		user
</details>

<details>
	<summary>
		each file and directyory in a partition is known by a unique inode _____
	</summary>
		number
</details>

<details>
	<summary>
		The command strace _____
	</summary>
		traces signals and system calls
</details>

<details>
	<summary>
		the syscall _____ copies bytes from of memory to a file. Blocks
	</summary>
		write
</details>

<details>
	<summary>
		_____ expose functionalities of the operating system to programs.
	</summary>
		system calls
</details>

<details>
	<summary>
		"_____ performs ""memory mapping"" of pages to the process address space. munmap can then be used to unmap them."
	</summary>
		mmap
</details>

<details>
	<summary>
		A _____ represents one end of a connection as a channel of communication.
	</summary>
		socket
</details>

<details>
	<summary>
		"mmap performs ""memory mapping"" of pages to the process address space. _____ can then be used to unmap them."
	</summary>
		munmap
</details>

<details>
	<summary>
		the file permission classes are user, _____, other
	</summary>
		group
</details>

<details>
	<summary>
		the _____ for files are open(), close(), read() and write()
	</summary>
		syscalls
</details>

<details>
	<summary>
		_____ changes permissions of an existing file/directory. The invoking process' EUID must be 0, or match the owner of that file/directory.
	</summary>
		chmod
</details>

<details>
	<summary>
		Signals can either be sent by _____ or the kill syscall
	</summary>
		the kernel
</details>

<details>
	<summary>
		a partition's root directory always has inode number _____
	</summary>
		2
</details>

<details>
	<summary>
		the syscall _____ copies bytes from a file to memory. Blocks.
	</summary>
		read
</details>

<details>
	<summary>
		each process has 3 user IDs: real ID (the owning user) _____ saved ID (set by exec to match the effective ID)
	</summary>
		effective ID (determines privileges)
</details>

<details>
	<summary>
		_____ changes the owner of an existing file/directory. The EUID of the invoker must be 0 or the owner of the file/directory.
	</summary>
		chown
</details>

<details>
	<summary>
		A file is ready to be released/overwritten once its _____'s link count equals 0.
	</summary>
		inode
</details>

<details>
	<summary>
		the syscalls for files are _____, close(), read() and write()
	</summary>
		open()
</details>

<details>
	<summary>
		Are syscalls ran inside the kernel? _____
	</summary>
		No - they're only ever called from inside a process. Every process has its own copy of available syscall definitions inside its address space. This avoids making a CPU-expensive context switch to the kernel.
</details>

<details>
	<summary>
		the file permission classes are user, group, _____
	</summary>
		other
</details>

