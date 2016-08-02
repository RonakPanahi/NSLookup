# About

nslookup is a Unix utility that converts hostnames to IP addresses and IP addresses to hostnames. It has two modes: interactive and command line. If you enter a hostname on the command line, nslookup prints the IP address of that host. If you enter an IP address on the command line, nslookup prints the hostname. If no hostname or IP address is entered  on the command line, nslookup enters interactive mode, in which it reads hostnames and IP addresses from input and echoes back the corresponding IP addresses or hostnames until you type “exit”.

Modify the nslookup functionality in this lab assignment such that your program also identifies the class or category of the IP address. That is, each time that you type in a hostname or IP address the program should not only display the corresponding IP address or hostname, it should also print out its IP address (network) class (A, B, C, or D).

