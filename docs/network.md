<details>
	<summary>
		The command _____ displays the status of the network
	</summary>
		netstat
</details>

<details>
	<summary>
		The command netstat _____
	</summary>
		displays the status of the network
</details>

<details>
	<summary>
		Predefined ports used by the OS for short-lived client sockets are called _____ ports.
	</summary>
		Ephemeral
</details>

<details>
	<summary>
		The command ip link set veth1 netns ns1 _____
	</summary>
		adds a virtual ethernet interface to a network namespace
</details>

<details>
	<summary>
		The command _____ creates a network namespace
	</summary>
		ip netns add ns1
</details>

<details>
	<summary>
		The command _____ traces the route to a given host
	</summary>
		traceroute
</details>

<details>
	<summary>
		The command ip link _____
	</summary>
		lists network interfaces on the localhost
</details>

<details>
	<summary>
		The command ethtool _____
	</summary>
		shows Ethernet card settings
</details>

<details>
	<summary>
		The command ip addr _____
	</summary>
		shows network interfaces on the host system
</details>

<details>
	<summary>
		The command ip -n ns1 addr add 192.168.15.1 dev veth1  _____ ip -n ns1 link set veth1 up  ip -n ns2 link set veth2 up  assigns an IP to a network namespace
	</summary>
		ip -n ns2 addr add 192.168.15.2 dev veth2
</details>

<details>
	<summary>
		The command ip netns exec _____
	</summary>
		can be used to run commands inside a network namespace
</details>

<details>
	<summary>
		The command _____ displays remote hosts connected to yours on port 3333
	</summary>
		netstat -a | grep 3333
</details>

<details>
	<summary>
		The _____ file is a list of hostname-to-IP address mappings for resolving hostnames (DNS)
	</summary>
		/etc/hosts
</details>

<details>
	<summary>
		The command nslookup _____
	</summary>
		queries a website's name server
</details>

<details>
	<summary>
		The command _____ shows network interfaces on the host system
	</summary>
		ip addr
</details>

<details>
	<summary>
		To connect several network namespaces you need a virtual _____, ex. Linux Bridge or Open vSwitch
	</summary>
		switch / bridge network
</details>

<details>
	<summary>
		Can network namespaces (netns) implement network isolation? _____
	</summary>
		Yes
</details>

<details>
	<summary>
		The command ip -n ns1 link _____
	</summary>
		lists network interfaces inside a namespace
</details>

<details>
	<summary>
		The command _____ can be used to run commands inside a network namespace
	</summary>
		ip netns exec
</details>

<details>
	<summary>
		The command ip -n ns1 link del veth1 _____
	</summary>
		deletes a veth pair between namespaces
</details>

<details>
	<summary>
		The command ip route add blackhole $BANNED_IP _____
	</summary>
		blocks an IP from connecting to your host
</details>

<details>
	<summary>
		The tracert command uses the _____ network protocol
	</summary>
		ICMP
</details>

<details>
	<summary>
		The command ip link add veth1 type veth peer name veth2 _____
	</summary>
		links two virtual ethernet interfaces
</details>

<details>
	<summary>
		The command _____ queries a website's name server
	</summary>
		nslookup
</details>

<details>
	<summary>
		The command traceroute _____
	</summary>
		traces the route to a given host
</details>

<details>
	<summary>
		The command _____ links two virtual ethernet interfaces
	</summary>
		ip link add veth1 type veth peer name veth2
</details>

<details>
	<summary>
		The command _____ ip -n ns2 addr add 192.168.15.2 dev veth2  ip -n ns1 link set veth1 up  ip -n ns2 link set veth2 up  assigns an IP to a network namespace
	</summary>
		ip -n ns1 addr add 192.168.15.1 dev veth1
</details>

<details>
	<summary>
		The command ip -n ns1 addr add 192.168.15.1 dev veth1  ip -n ns2 addr add 192.168.15.2 dev veth2  ip -n ns1 link set veth1 up  _____ assigns an IP to a network namespace
	</summary>
		ip -n ns2 link set veth2 up
</details>

<details>
	<summary>
		The command ip -n ns1 addr add 192.168.15.1 dev veth1  ip -n ns2 addr add 192.168.15.2 dev veth2  ip -n ns1 link set veth1 up  ip -n ns2 link set veth2 up  _____
	</summary>
		assigns an IP to a network namespace
</details>

<details>
	<summary>
		The command ip netns add ns1 _____
	</summary>
		creates a network namespace
</details>

<details>
	<summary>
		"The command ip link add veth1 type veth peer name veth1-bridge ip link set veth1-bridge master v-net-0  _____"
	</summary>
		links a veth interface ""veth1"" to a bridge network ""v-net-0""
</details>

<details>
	<summary>
		The command _____ lists network interfaces on the localhost
	</summary>
		ip link
</details>

<details>
	<summary>
		The command _____ finds the hostname of an IP address.
	</summary>
		dig
</details>

<details>
	<summary>
		The _____ file specifies the DNS server and domain suffix of the system.
	</summary>
		/etc/resolv.conf
</details>

<details>
	<summary>
		The command ip -n ns1 addr add 192.168.15.1 dev veth1  ip -n ns2 addr add 192.168.15.2 dev veth2  _____ ip -n ns2 link set veth2 up  assigns an IP to a network namespace
	</summary>
		ip -n ns1 link set veth1 up
</details>

<details>
	<summary>
		The command _____ blocks an IP from connecting to your host
	</summary>
		ip route add blackhole $BANNED_IP
</details>

<details>
	<summary>
		The command netstat -a | grep 3333 _____
	</summary>
		displays remote hosts connected to yours on port 3333
</details>

<details>
	<summary>
		The command _____ lists network interfaces inside a namespace
	</summary>
		ip -n ns1 link
</details>

<details>
	<summary>
		"The command _____ links a veth interface ""veth1"" to a bridge network ""v-net-0"""
	</summary>
		ip link add veth1 type veth peer name veth1-bridge ip link set veth1-bridge master v-net-0
</details>

<details>
	<summary>
		The command dig _____
	</summary>
		finds the hostname of an IP address.
</details>

<details>
	<summary>
		The command _____ creates a new bridge network
	</summary>
		ip link add v-net-0 type bridge ip link set dev v-net-0 up
</details>

<details>
	<summary>
		The command _____ adds a virtual ethernet interface to a network namespace
	</summary>
		ip link set veth1 netns ns1
</details>

<details>
	<summary>
		The ping command uses the _____ network protocol
	</summary>
		ICMP
</details>

<details>
	<summary>
		The command  ip link add v-net-0 type bridge ip link set dev v-net-0 up  _____
	</summary>
		creates a new bridge network
</details>

<details>
	<summary>
		The command _____ deletes a veth pair between namespaces
	</summary>
		ip -n ns1 link del veth1
</details>

<details>
	<summary>
		The command _____ shows Ethernet card settings
	</summary>
		ethtool
</details>

