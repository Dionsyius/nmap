# nmap
FIND NETWORK  VULN/LIVE HOST OR TARGET TO HACK





$ sudo nmap -sP (ip)                                 -Ping ip


$ sudo nmap -Pn                                    -To unblock ping probes


$ sudo nmap -sS (dns or ip)                      -For stealth ping


sudo nmap -sS -p (port) (dns or ip)               -To stealth ping port


sudo nmap -sT (ip host)                              -Full tcp connection


$ sudo nmap -O  (ip host)                             -For Os Detection and ports


$ sudo nmap -A  (network ip)


$ sudo nmap -sS -D  (fake ip)  (target ip)            -To cover your tracks


$ sudo nmap --script vuln (ip)      
