# Network-Configuration

<p>The following is a list of network configurations on an air-gaped network. 
However, to address the strange choice of using a 10.0.0.0/24, I have done so as my main computer that I use is connected to a 192.0.0.0/24 address with a default gateway. 
This helps mitigate network malfunctions with my main rig using 2 addresses from 2 different routers. 
I know and understand how VLAN's would prevent the need for such a complicated set up, but my living situation prevents me from accessing accessing and modifying the configuration on the internet connected router.</p>


<h2>IP Ranges</h2>

  - [Networking Equipment]
     - 10.0.0.1-10
  - [Server Equipment/Services]
     - 10.0.0.11-30
  - [Personal Computers]
     - 10.0.0.31-50
  - [Security Environment]
     - 10.0.0.100-110

<h2>IP/Mac Addresses</h2>

<h3>Router</h3>  

  -  IP:     10.0.0.1
  -  Mac:    c8-9e-43-b1-b6-62
  -  DHCP:   ENABLED    

[L3 Switch 16 Port](https://github.com/MarcusAndrews-lab/Switch-ports)

  -  IP:    10.0.0.2
  -  Mac:  	00-1b-2f-c2-56-27
  -  DHCP:  DISABLED

[L3 Switch 8 Port](https://github.com/MarcusAndrews-lab/Switch-ports)

  -  IP:    10.0.0.3
  -  Mac:  	78-D2-94-B3-2B-68 
  -  DHCP:  DISABLED


<h3>Proxmox Server</h3>
(Note: Upon further inspection the 10-Gb nic used seems to have started crashing, I will need to look into this further)

  -  IP:   10.0.0.11
  -  BackUp IP: 10.0.0.100
  -  Mac:  00-00-00-00-00-00

<h3>TrueNas Server</h3>

  -  IP:   10.0.0.16
  -  Mac:  00-00-00-00-00-00
    
<h3>Main PC</h3>

  -  IP: 10.0.0.31



<h2>VLAN's</h2>
<p>None</p>
