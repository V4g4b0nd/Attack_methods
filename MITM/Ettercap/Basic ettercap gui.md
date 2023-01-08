<h1>ettercap GUI sheet</h1>

<h2>Notes:</h2>
 - All the systems must be connected to same network<br/>
 - Need to echo ip forwarding value to 1 before using Wireshark<br/>
 - HTTP websites are vulnerable<br/>

<p align="Left">

Arp poisoning
 
           ipconfig or ifocnfig
           arp -a - shows arp table
           note down the IP address and default gateway of the machine
 
Poisoning using ettter cap

          interface and start
          Click dots, select host and scan
          go to dots, hosts and show hosts
          give us the list of found hosts

          Add host as target 1 and router as target 2

          Go to menu, (Globe icon on right) and start the attack (Arp poisoning)

          Capture arp traffic in wireshark

          use Arp - a in victim host we can see the mac of Attack box as default gateway 


