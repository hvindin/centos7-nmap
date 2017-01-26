# nmap running on Centos7

This container contains nmap running on a Centos7 base.  

To run this container execute the following:  

        docker run --rm docker.io/hvindin/centos7-nmap:latest <NMAP COMMANDS>

Or, if you have some strange DNS or networking stuff going on, a good catch all is to run

        docker run --rm --network=host docker.io/hvindin/centos-nmap:latest <NMAP COMMANDS>
