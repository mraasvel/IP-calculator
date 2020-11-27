**USAGE**

1. make to create executable "calc.exe"
2. ./calc to execute program

Input:

	IP + Netmask

	IP format: n1.n2.n3.n4
	Netmask: '24' or 255.255.255.0 (CIDR or Dotted Decimal notation)

Output for IP calculator:

	Address:		n1.n2.n3.n4		binary rep of address.
	Netmask:		n1.n2.n3.n4		binary rep of NM.
	Wildcard:		n1.n2.n3.n4		binary rep of WC.
	=>
	Network:	n1.n2.n3.n4		binary rep of NW (class type)
	Broadcast:	n1.n2.n3.n4		binary rep of BC
	Hostmin:	n1.n2.n3.n4		binary rep of HMin
	Hostmax:	n1.n2.n3.n4		binary rep of HMax
	Hosts/net:	[Amount] - (2 ^ (32 - netmask) - 1).

Output for just netmask:
	Netmask:	[Dotted Decimal] [Binary] [CIDR]
	Hosts/net:	[Amount]
