# firewallstuff

##fortigate show flow to an ip
diagnose debug reset
diagnose debug flow filter daddr 8.8.8.8
diagnose debug flow show console enable
diagnose debug enable
diagnose debug flow trace start 20
diagnose debug disable
