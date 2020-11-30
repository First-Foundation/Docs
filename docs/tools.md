##NMAP
```
nmap -p- -v -Pn -oN nmap.quick <IP>
nmap -sVC -p <list,of,ports> -Pn -oN nmap.service <IP>
nmap -T4 -A -p- -n -Pn -oN nmap.full <IP>
nmap -sV -v -Pn --script vuln -oN nmap.vuln <IP>
nmap -T4 -A -p- -n -Pn -oN ./nmap.tcp <IP>
nmap -p- -v -sU -Pn -oN ./nmap.udp <IP>
```

##CEWL
```
cewl -e http://<IP>/site.php> #Gathers Emails
cewl http://site.com
```