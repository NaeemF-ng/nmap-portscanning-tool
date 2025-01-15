# nmap-portscanning-tool

Overview: In this repository I will be explaining what nmap is and how i've been using it for my hands on experience within my Homelab and what I think of the tool.

Intro to nmap: Nmap is a tool for network discovery, security auditing, and vulnerability asssessment. The tool is very important in the phase of reconnaissance as it provides valuable information such as what are ports are open, software thats running, versions regarding services, etc. 

How i've been using it: I've been using nmap to scan against my ubuntu target machine. When I first began using nmap for the first time, I started with the basic scan "nmap <target>" just to get the basics down. Then I began playing around with the add ons such "nmap -sV -O <target>" and port specification , which are really my go to's after the basic scan. The -sV and -O  tells nmap to scan for running services within the target as well the operating systems. I just started using scripts for nmap, I'm seeing that they're very helpful and provide great information. As an example the ftp port on my metasploitable machine is open, i've been using the command nmap -p 21 --script ftp-anon  <target>. This tells nmap to see if the ftp service on the target machine allows anonymous login. I haven't used the all of the advanced scans such as the xmas, zombies, dns zone transfer,etc. However, I will try to incorporate them into my routine as I continue.

Thoughts on nmap: I really enjoy using nmap, to reiterate it really is a big help in terms of strategizing for reconnaissance.
