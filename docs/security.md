<details>
	<summary>
		The command useradd _____
	</summary>
		creates a new user account.
</details>

<details>
	<summary>
		The command _____ changes a file's owner or group.
	</summary>
		chown
</details>

<details>
	<summary>
		The command _____ changes a user's password.
	</summary>
		passwd
</details>

<details>
	<summary>
		Default shell files should have default value of _____ set, for example to 077
	</summary>
		umask
</details>

<details>
	<summary>
		Debian's password encryption algorithm is set by Pluggable Authentication Modules (PAM) in the _____ file
	</summary>
		/etc/pam.d/common-passwd
</details>

<details>
	<summary>
		Encrypted Linux passwords all have the same _____, even if the unencrypted passwords do not
	</summary>
		length
</details>

<details>
	<summary>
		the chmod _____ permission means READ permission for owner, group and public
	</summary>
		0444
</details>

<details>
	<summary>
		The command _____ modifies a group
	</summary>
		groupmod
</details>

<details>
	<summary>
		The command _____ modifies a user account.
	</summary>
		usermod
</details>

<details>
	<summary>
		gVisor is a _____ that can sandbox syscalls in userspace via restricted seccomp filters
	</summary>
		kernel security module
</details>

<details>
	<summary>
		The /etc/passwd file stores _____
	</summary>
		users and data about them
</details>

<details>
	<summary>
		The _____ file contains group definitions.
	</summary>
		/etc/group
</details>

<details>
	<summary>
		the chmod 0111 permission means EXECUTE permission for _____
	</summary>
		owner, group and public
</details>

<details>
	<summary>
		Login names can never contain colons or newlines - these characters are used as field and entry separators in the _____ file respectively
	</summary>
		/etc/passwd
</details>

<details>
	<summary>
		Each line of the /etc/shadow password file represents a user. The user's fields are separated by colons: username:password:Last password change:Minimum days required between password changes:_____:password expiration warning duration:password expiration ban deadline:{{c10::account expiration date}}
	</summary>
		Maximum days between password changes
</details>

<details>
	<summary>
		_____ filters decide which syscalls are allowed inside in a system. This prevents signals from being arbitrarily ran by an attacker, or being used to break out of a Linux namespace via unshare
	</summary>
		seccomp
</details>

<details>
	<summary>
		The root, system, or wheel group always has GID of _____
	</summary>
		0
</details>

<details>
	<summary>
		AppArmor profiles in complain mode _____
	</summary>
		report violations
</details>

<details>
	<summary>
		Each line in the /etc/passwd file represents a user. A line's colon-separated fields represent: _____:password:UID:Default GID:comments:home:shell
	</summary>
		username
</details>

<details>
	<summary>
		AppArmor profiles in _____ mode block access to disallowed resources
	</summary>
		enforcing
</details>

<details>
	<summary>
		Each line of the /etc/shadow password file represents a user. The user's fields are separated by colons: _____:password:Last password change:Minimum days required between password changes:Maximum days between password changes:password expiration warning duration:password expiration ban deadline:{{c10::account expiration date}}
	</summary>
		username
</details>

<details>
	<summary>
		The command _____ sets a password for a user
	</summary>
		passwd [username]
</details>

<details>
	<summary>
		The command _____ reconciles the contents of the /etc/shadow and /etc/passwd files
	</summary>
		pwconv
</details>

<details>
	<summary>
		root user's UID always equals _____
	</summary>
		0
</details>

<details>
	<summary>
		the chmod 0444 permission means _____ permission for owner, group and public
	</summary>
		READ
</details>

<details>
	<summary>
		The command _____ sets a group's password, allowing users to enter it
	</summary>
		gpasswd
</details>

<details>
	<summary>
		RHEL's password encryption algorithm is set in the /etc/login.defs file, or through the _____ command
	</summary>
		authconfig
</details>

<details>
	<summary>
		The command _____ can change a user’s configuration through editing the /etc/passwd file
	</summary>
		vipw
</details>

<details>
	<summary>
		Each line of the /etc/shadow password file represents a user. The user's fields are separated by colons: username:password:Last password change:Minimum days required between password changes:Maximum days between password changes:password expiration warning duration:_____:{{c10::account expiration date}}
	</summary>
		password expiration ban deadline
</details>

<details>
	<summary>
		seccomp filters decide which _____ are allowed inside in a system. This prevents signals from being arbitrarily ran by an attacker, or being used to break out of a Linux namespace via unshare
	</summary>
		syscalls
</details>

<details>
	<summary>
		Debian's password encryption algorithm is set by _____ in the /etc/pam.d/common-passwd file
	</summary>
		Pluggable Authentication Modules (PAM)
</details>

<details>
	<summary>
		the chmod 0111 permission means _____ permission for owner, group and public
	</summary>
		EXECUTE
</details>

<details>
	<summary>
		The command userdel _____
	</summary>
		deletes a user account.
</details>

<details>
	<summary>
		Each line of the /etc/shadow password file represents a user. The user's fields are separated by colons: username:password:_____:Minimum days required between password changes:Maximum days between password changes:password expiration warning duration:password expiration ban deadline:{{c10::account expiration date}}
	</summary>
		Last password change
</details>

<details>
	<summary>
		Each line in the /etc/passwd file represents a user. A line's colon-separated fields represent: username:password:UID:Default GID:comments:home:_____
	</summary>
		shell
</details>

<details>
	<summary>
		Each line in the /etc/passwd file represents a user. A line's colon-separated fields represent: username:password:UID:Default GID:comments:_____:shell
	</summary>
		home
</details>

<details>
	<summary>
		Pseudo-users have a _____, and therefore cannot be logged into. They are commonly defined as owners of commands and configuration files
	</summary>
		fake login shell
</details>

<details>
	<summary>
		_____ is a kernel security module that confines programs to a limited set of resources, reducing an application's attack surface
	</summary>
		AppArmor
</details>

<details>
	<summary>
		The /etc/shadow password file is readable only by _____
	</summary>
		the superuser
</details>

<details>
	<summary>
		"The command _____ searches the /var/log/ directory for usages of the word ""login"""
	</summary>
		grep login /var/log/*
</details>

<details>
	<summary>
		Each line of the /etc/shadow password file represents a user. The user's fields are separated by colons: username:password:Last password change:Minimum days required between password changes:Maximum days between password changes:_____:password expiration ban deadline:{{c10::account expiration date}}
	</summary>
		password expiration warning duration
</details>

<details>
	<summary>
		sh reads _____ before reading ~/.profile and ~/.bash_profile
	</summary>
		/etc/profile
</details>

<details>
	<summary>
		the chmod 0222 permission means _____ permission for owner, group and public
	</summary>
		WRITE
</details>

<details>
	<summary>
		Never manually edit /etc/passwd, /etc/group or /etc/shadow. Use the commands useradd, adduser, usermod, _____, vipw, vipw -s and chsh instead
	</summary>
		pw
</details>

<details>
	<summary>
		Are login names case-sensitive? _____
	</summary>
		Yes
</details>

<details>
	<summary>
		The command _____ deletes a user account.
	</summary>
		userdel
</details>

<details>
	<summary>
		Human user UIDs should equal to _____
	</summary>
		1000 or higher
</details>

<details>
	<summary>
		A user's group memberships equals the union of those defined for the user in /etc/passwd and _____
	</summary>
		/etc/group
</details>

<details>
	<summary>
		gVisor is a kernel security module that can _____ syscalls in userspace via restricted seccomp filters
	</summary>
		sandbox
</details>

<details>
	<summary>
		AppArmor profiles configure access to capabilities, network access, file permissions, either in _____ or complain mode
	</summary>
		enforcing
</details>

<details>
	<summary>
		The _____ file stores users and data about them
	</summary>
		/etc/passwd
</details>

<details>
	<summary>
		Never manually edit /etc/passwd, /etc/group or /etc/shadow. Use the commands useradd, _____, usermod, pw, vipw, vipw -s and chsh instead
	</summary>
		adduser
</details>

<details>
	<summary>
		The command chown _____
	</summary>
		changes a file's owner or group.
</details>

<details>
	<summary>
		A Linux user is represented by its number: the _____
	</summary>
		user ID or UID
</details>

<details>
	<summary>
		A user's group memberships equals the union of those defined for the user in _____ and /etc/group
	</summary>
		/etc/passwd
</details>

<details>
	<summary>
		The command passwd _____
	</summary>
		changes a user's password.
</details>

<details>
	<summary>
		New files are typically owned by the user's _____ group
	</summary>
		effective
</details>

<details>
	<summary>
		Edit /etc/group by running _____ and /etc/gshadow by running vigr -s
	</summary>
		vigr
</details>

<details>
	<summary>
		Do login names have to be unique? _____
	</summary>
		Yes
</details>

<details>
	<summary>
		Each line in the /etc/passwd file represents a _____. A line's colon-separated fields represent: username:password:UID:Default GID:comments:home:shell
	</summary>
		user
</details>

<details>
	<summary>
		The command whoami displays _____
	</summary>
		the currently logged in user
</details>

<details>
	<summary>
		Group names should be limited to _____ characters for compatibility
	</summary>
		8
</details>

<details>
	<summary>
		AppArmor profiles in enforcing mode _____
	</summary>
		block access to disallowed resources
</details>

<details>
	<summary>
		The _____ password file is readable only by the superuser
	</summary>
		/etc/shadow
</details>

<details>
	<summary>
		A line in the /etc/group file represents a single group. Its fields are separated by colons: Name:Password:GID:_____
	</summary>
		Members, separated by commas
</details>

<details>
	<summary>
		Each line in the /etc/passwd file represents a user. A line's colon-separated fields represent: username:password:UID:_____:comments:home:shell
	</summary>
		Default GID
</details>

<details>
	<summary>
		The command _____ displays the groups a user belongs to
	</summary>
		groups
</details>

<details>
	<summary>
		Never manually edit /etc/passwd, /etc/group or /etc/shadow. Use the commands _____, adduser, usermod, pw, vipw, vipw -s and chsh instead
	</summary>
		useradd
</details>

<details>
	<summary>
		AppArmor profiles configure access to capabilities, network access, file permissions, either in enforcing or _____ mode
	</summary>
		complain
</details>

<details>
	<summary>
		Each line in the /etc/passwd file represents a user. A line's colon-separated fields represent: username:password:_____:Default GID:comments:home:shell
	</summary>
		UID
</details>

<details>
	<summary>
		Each line of the /etc/shadow password file represents a user. The user's fields are separated by colons: username:_____:Last password change:Minimum days required between password changes:Maximum days between password changes:password expiration warning duration:password expiration ban deadline:{{c10::account expiration date}}
	</summary>
		password
</details>

<details>
	<summary>
		The command usermod _____
	</summary>
		modifies a user account.
</details>

<details>
	<summary>
		The command id displays _____
	</summary>
		user and group ID's
</details>

<details>
	<summary>
		Never manually edit /etc/passwd, /etc/group or /etc/shadow. Use the commands useradd, adduser, usermod, pw, _____, vipw -s and chsh instead
	</summary>
		vipw
</details>

<details>
	<summary>
		the chmod _____ permission means EXECUTE permission for owner, group and public
	</summary>
		0111
</details>

<details>
	<summary>
		AppArmor _____ configure access to capabilities, network access, file permissions, either in enforcing or complain mode
	</summary>
		profiles
</details>

<details>
	<summary>
		The command _____ adds a user group
	</summary>
		groupadd
</details>

<details>
	<summary>
		The /etc/shadow file contains _____
	</summary>
		encrypted passwords.
</details>

<details>
	<summary>
		_____ profiles configure access to capabilities, network access, file permissions, either in enforcing or complain mode
	</summary>
		AppArmor
</details>

<details>
	<summary>
		AppArmor is a kernel security module that confines programs to _____, reducing an application's attack surface
	</summary>
		a limited set of resources
</details>

<details>
	<summary>
		The _____ file contains encrypted passwords.
	</summary>
		/etc/shadow
</details>

<details>
	<summary>
		Linux passwords are encrypted with a random _____, allowing them to have several encrypted forms, especially if several users use the same password
	</summary>
		salt
</details>

<details>
	<summary>
		Linux typically encrypts passwords under the _____ cryptographic function
	</summary>
		SHA-512
</details>

<details>
	<summary>
		Each line in the _____ file represents a user. A line's colon-separated fields represent: username:password:UID:Default GID:comments:home:shell
	</summary>
		/etc/passwd
</details>

<details>
	<summary>
		Edit _____ by running vigr and /etc/gshadow by running vigr -s
	</summary>
		/etc/group
</details>

<details>
	<summary>
		The command groupadd _____
	</summary>
		adds a user group
</details>

<details>
	<summary>
		The command vipw can change a user’s configuration through editing the _____ file
	</summary>
		/etc/passwd
</details>

<details>
	<summary>
		the chmod 0444 permission means READ permission for _____
	</summary>
		owner, group and public
</details>

<details>
	<summary>
		Human groups should have GID of _____
	</summary>
		1000 or higher
</details>

<details>
	<summary>
		The commands useradd, usermod and userdel can be configured via the files /etc/login.defs and _____
	</summary>
		/etc/default/useradd
</details>

<details>
	<summary>
		the chmod _____ permission means WRITE permission for owner, group and public
	</summary>
		0222
</details>

<details>
	<summary>
		The command _____ changes a user's login shell
	</summary>
		chsh
</details>

<details>
	<summary>
		The command _____ lists users who are logged in.
	</summary>
		users
</details>

<details>
	<summary>
		A line in the /etc/group file represents a single group. Its fields are separated by colons: _____:Password:GID:Members, separated by commas
	</summary>
		Name
</details>

<details>
	<summary>
		Never manually edit /etc/passwd, /etc/group or /etc/shadow. Use the commands useradd, adduser, usermod, pw, vipw, _____ and chsh instead
	</summary>
		vipw -s
</details>

<details>
	<summary>
		The command groups displays _____
	</summary>
		the groups a user belongs to
</details>

<details>
	<summary>
		A line in the /etc/group file represents a single group. Its fields are separated by colons: Name:Password:_____:Members, separated by commas
	</summary>
		GID
</details>

<details>
	<summary>
		Edit /etc/group by running vigr and /etc/gshadow by running _____
	</summary>
		vigr -s
</details>

<details>
	<summary>
		A line in the _____ file represents a single group. Its fields are separated by colons: Name:Password:GID:Members, separated by commas
	</summary>
		/etc/group
</details>

<details>
	<summary>
		The _____ file configures password expiration, encryption algorithms, UID ranges and GID ranges
	</summary>
		login.defs
</details>

<details>
	<summary>
		The command pwconv reconciles the contents of the /etc/shadow and _____ files
	</summary>
		/etc/passwd
</details>

<details>
	<summary>
		Each line of the _____ password file represents a user. The user's fields are separated by colons: username:password:Last password change:Minimum days required between password changes:Maximum days between password changes:password expiration warning duration:password expiration ban deadline:{{c10::account expiration date}}
	</summary>
		/etc/shadow
</details>

<details>
	<summary>
		The command users _____
	</summary>
		lists users who are logged in.
</details>

<details>
	<summary>
		_____ is a kernel security module that can sandbox syscalls in userspace via restricted seccomp filters
	</summary>
		gVisor
</details>

<details>
	<summary>
		The command _____ displays the currently logged in user
	</summary>
		whoami
</details>

<details>
	<summary>
		The commands useradd, usermod and userdel can be configured via the files _____ and /etc/default/useradd
	</summary>
		/etc/login.defs
</details>

<details>
	<summary>
		Each line of the /etc/shadow password file represents a user. The user's fields are separated by colons: username:password:Last password change:_____:Maximum days between password changes:password expiration warning duration:password expiration ban deadline:{{c10::account expiration date}}
	</summary>
		Minimum days required between password changes
</details>

<details>
	<summary>
		Each line in the /etc/passwd file represents a user. A line's colon-separated fields represent: username:password:UID:Default GID:_____:home:shell
	</summary>
		comments
</details>

<details>
	<summary>
		Users managed through LDAP (or other directory service) might have special entries in the /etc/passwd file beginning with _____, integrating the file with the directory service
	</summary>
		+ or -
</details>

<details>
	<summary>
		The /etc/group file contains _____
	</summary>
		group definitions.
</details>

<details>
	<summary>
		The _____ GID is used during creation of new files and directories
	</summary>
		default
</details>

<details>
	<summary>
		Edit /etc/group by running vigr and _____ by running vigr -s
	</summary>
		/etc/gshadow
</details>

<details>
	<summary>
		Grant a user sudo privileges by adding their username to the _____ file
	</summary>
		sudoers
</details>

<details>
	<summary>
		The _____ group always has GID of 0
	</summary>
		root, system, or wheel
</details>

<details>
	<summary>
		You can generate AppArmor profiles using the _____ generation tool
	</summary>
		Bane (https://github.com/jfrazelle/bane)
</details>

<details>
	<summary>
		Each line in the /etc/passwd file represents a user. A line's colon-separated fields represent: username:_____:UID:Default GID:comments:home:shell
	</summary>
		password
</details>

<details>
	<summary>
		gVisor is a kernel security module that can sandbox _____ in userspace via restricted seccomp filters
	</summary>
		syscalls
</details>

<details>
	<summary>
		seccomp filters decide which syscalls are allowed inside in a system. This prevents signals from being arbitrarily ran by an attacker, or being used to break out of a Linux namespace via _____
	</summary>
		unshare
</details>

<details>
	<summary>
		A line in the /etc/group file represents a single group. Its fields are separated by colons: Name:_____:GID:Members, separated by commas
	</summary>
		Password
</details>

<details>
	<summary>
		The command _____ displays user and group ID's
	</summary>
		id
</details>

<details>
	<summary>
		The command chage -d 0 username _____
	</summary>
		invalidates a user’s password and forces an update
</details>

<details>
	<summary>
		gVisor is a kernel security module that can sandbox syscalls in userspace via _____
	</summary>
		restricted seccomp filters
</details>

<details>
	<summary>
		The _____ directory holds sample startup files
	</summary>
		/etc/skel
</details>

<details>
	<summary>
		The command _____ invalidates a user’s password and forces an update
	</summary>
		chage -d 0 username
</details>

<details>
	<summary>
		AppArmor is a _____ that confines programs to a limited set of resources, reducing an application's attack surface
	</summary>
		kernel security module
</details>

<details>
	<summary>
		It is best practice that a human user should have the same consistent login name and _____ across all machines they use
	</summary>
		UID
</details>

<details>
	<summary>
		The command groupmod_____
	</summary>
		modifies a group
</details>

<details>
	<summary>
		The command groupdel _____
	</summary>
		deletes a group
</details>

<details>
	<summary>
		The /etc/skel directory holds _____
	</summary>
		sample startup files
</details>

<details>
	<summary>
		It is best practice that a human user should have the same consistent _____ and UID across all machines they use
	</summary>
		login name
</details>

<details>
	<summary>
		The _____ file defines groups
	</summary>
		/etc/group
</details>

<details>
	<summary>
		The command _____ creates a new user account.
	</summary>
		useradd
</details>

<details>
	<summary>
		LDAP and /etc/passwd integration can be configured in the _____ file
	</summary>
		/etc/nsswitch.conf
</details>

<details>
	<summary>
		The command _____ deletes a group
	</summary>
		groupdel
</details>

<details>
	<summary>
		RHEL's password encryption algorithm is set in the _____ file, or through the authconfig command
	</summary>
		/etc/login.defs
</details>

<details>
	<summary>
		gVisor is a kernel security module that can sandbox syscalls in _____ via restricted seccomp filters
	</summary>
		userspace
</details>

<details>
	<summary>
		Linux limits login length to _____ characters
	</summary>
		32
</details>

<details>
	<summary>
		Never manually edit /etc/passwd, /etc/group or /etc/shadow. Use the commands useradd, adduser, _____, pw, vipw, vipw -s and chsh instead
	</summary>
		usermod
</details>

<details>
	<summary>
		The command pwconv reconciles the contents of the _____ and /etc/passwd files
	</summary>
		/etc/shadow
</details>

<details>
	<summary>
		To manually create a new Linux user, add them into the files: _____
	</summary>
		/etc/passwd, /etc/shadow and /etc/group
</details>

<details>
	<summary>
		the chmod 0222 permission means WRITE permission for _____
	</summary>
		owner, group and public
</details>

<details>
	<summary>
		Never manually edit /etc/passwd, /etc/group or /etc/shadow. Use the commands useradd, adduser, usermod, pw, vipw, vipw -s and _____ instead
	</summary>
		chsh
</details>

<details>
	<summary>
		Users managed through LDAP (or other directory service) might have special entries in the _____ file beginning with + or -, integrating the file with the directory service
	</summary>
		/etc/passwd
</details>

<details>
	<summary>
		"The command grep login /var/log/* _____"
	</summary>
		searches the /var/log/ directory for usages of the word ""login""
</details>

