# B64 encoded tools 
List of CTF tools base64 encoded to download on Airgapped machines 

To retrieve installer run following on terminal 

- base64 -d example.b64 > example.(sh,rpm,deb)
  
- chmod +x example.sh       #Not needed if .rpm or .deb
  
- ./example.sh

OR

-Sudo dpkg -i example.deb


TOOLS 

-Alien- used to convert .RPM to .DEB need if distro running is debian based 

-NMAP(installs as .rpm use alien)-for network discovery and security auditing, used to scan hosts, detect services, and identify vulnerabilitie

-




