# Nmap
A automated Nmap script that will do all the work for you 

# Summary
I have created this script as I was learning or to say exploring nmap scripts.  
The main goal for this script is to automate all of the process of recon/enumeration that is run every time, and instead focus our attention on real pen testing.  
  
This will ensure two things:  
	1) Automate nmap scans. 
	2) Always have some recon running in the background. 

Once you find the inital ports in around 10 seconds, you then can start manually looking into those ports, and let the rest run in the background with no interaction from your side whatsoever.  
  

# Features 
1. **Zenmap strategies**  Intense Scan , Intense Scan, Plus UDP , Intense Scan, all TCP ports , Intense Scan, no ping , Ping scan , Quick Scan , Quick traceroute , Regular Scan Slow comprehensive scan
1. **Firewall/IDS Evasion and Spoofing**  Intense Scan , Intense Scan, Plus UDP , Intense Scan, all TCP ports , Intense Scan no ping , Ping scan , Quick Scan , Quick traceroute , Regular Scan , Slow comprehensive scan
1. **Firewall/IDS Evasion and Spoofing**  Not intrusive , Default , Default or safe , Default and safe , All scripts \e[0m\n'
1. **Miscelaneous**  Detect Service Version , Operating System Scan , OS and Service Detect , Version Detect , Full Port Scan (TCP) , Full Port Scan (UDP/Very Slow) , Most Common Ports (TCP) , Most Common Ports (UDP) ,Faster Regular Scan 

I tried to make the script as efficient as possible, so that you would get the results as fast as possible, without duplicating any work.  

Feel free to send your pull requests and contributions xd
  

# Requirement

**Just a linux terminal with active internet connection with nmap install**
``` 
bash nmap.sh
```
**if dont work please use**
`dos2unix nmap.sh`

