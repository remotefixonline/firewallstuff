# firewallstuff
                ###FORTIGATE####
##fortigate show flow to an ip
diagnose debug reset
diagnose debug flow filter daddr 8.8.8.8
diagnose debug flow show console enable
diagnose debug enable
diagnose debug flow trace start 20
diagnose debug disable
##sniffer examples  
diagnose sniffer packet any 'host 8.8.8.8' 4 20 l
diagnose sniffer packet any 'host 8.8.8.8 and dst port 53' 4 10 a
diagnose sniffer packet wan1 'dst port (80 or 443)' 2 50 l
