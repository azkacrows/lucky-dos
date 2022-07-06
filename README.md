# lucky DOS.py

* This is my new update 
* This script have 3 type of ddos attack : SYNFLOOD | REQUEST | Pyslow
* Script has pyslow attack type which same like slowloris attack

# Note
* I worte this script for educational not for destructive purposes and illegal actions,so i won't responsible for that  


# Requires module
* termcolor
* colorama



# Usage
                                                               
        DDos python script | Script used for testing ddos | Ddos attack     
        

    usage: ./pyddos -t [target] -p [port] -t [number threads]

    optional arguments:
    -h, --help       show this help message and exit
    -v, --version    show program's version number and exit

    options:

    -d <ip|domain>   Specify your target such an ip or domain name
    -t <float>       Set timeout for socket
    -T <int>         Set threads number for connection (default = 1000)
    -p <int>         Specify port target (default = 80) |Only required with pyslow attack|
    -s <int>         Set sleep time for reconnection
    -i <ip address>  Specify spoofed ip unless use fake ip
    -Request         Enable request target
    -Synflood        Enable synflood attack
    -Pyslow          Enable pyslow attack
    --fakeip         Option to create fake ip if not specify spoofed ip

