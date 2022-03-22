# nmap
FIND NETWORK  VULN/LIVE HOST OR TARGET TO HACK




Nmapswitch                                          Description




$ sudo nmap -sP (ip)                                 -Ping ip


$ sudo nmap -Pn                                    -To unblock ping probes


$ sudo nmap -sS (dns or ip)                      -For stealth ping


sudo nmap -sS -p (port) (dns or ip)               -To stealth ping port


sudo nmap -sT (ip host)                              -Full tcp connection


$ sudo nmap -O  (ip host)                             -For Os Detection and ports


$ sudo nmap -A  (network ip)


$ sudo nmap -sS -D  (fake ip)  (target ip)            -To cover your tracks


$ sudo nmap --script vuln (ip)      


-sF                                                    FIN scan


-sl                                                   IDLE scan


-sL                                                    DNS scan


-sN                                                    NULL scan 


-sO                                                    Protocol scan


-sP                                                      PING scan


-sR                                                      RPC scan


-sS                                                       SYN scan


-sT                                                        TCP connect scan


-sW                                                       Window scan


-sX                                                        XMAS scan


-PI                                                      ICMP scan


-Po                                                      No ping


-PS                                                       SYN ping


-PT                                                        TCP ping


-oN                                                        Normal output


-oX                                                        XML output


-To                                                     Serial, slowest scan


-T1                                                           Serial, slowest scan


-T2                                                         Serial, normal speed scan


-T3                                                          Parallel, normal speed scan


-T4                                                                Parallel, fast scan
