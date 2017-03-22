# README

This document is used for the planning of (and maybe a finished version of) a cjdns cookbook. This cookbook will have everything a user needa to get up and running with cjdns, with recipes to use it to do cool stuff. This will hopefully absorb **all** exisiting cjdns documentation and become the de facto book for using cjdns.

### Table of Contents

1. Introduction 
    - What is cjdns? 
    - How does cjdns work?
    - What is a mesh network (basic intro)
    - Tell me the technical stuff! (crypto and dht at a glance)
2. Beginner
    1 Get Started!
        - Installation instructions (Linux, OSX, BSD, Windows)
        - Optimizing builds
        - Peering, make your own peering credentials
    2 Connect two Nodes!
        - Make your own isolated VPN
            - Maybe some troubleshooting
            - Try out some iperf3 and get your throughput
        - Connect to Hyperboria
        - Check out the included cjdns tools
        - Use some fc00 tools
        - Add yourself to the fc00 org map
    3 **Other stuff from the cjdns docs**    
3. Intermediate
    1 Node security 
        - Using iptables and ip6tables
        - Nmap scanning, etc.
    2 Hosting Setvices to the Net
        - Expose your exisiting website over cjdns (Apache and Nginx), 
        - Running other services like an IRCd, torrent tracker, BBS, etc. 
        - Reverse proxying existing clearnet stuff 
        - Exposing IPv4-only services
        - Bootstrap IPFS with Hype-only peers
    3 All-In-Wonder
        - tomesh's Rpi Prototype
        - Orange Pi Zero (eventually)
    4  Make a NAT'd gateway for a WLAN
4. Advanced
    1 Physical meshing
        - Use cjdns' layer 2 support
        - Use 802.11s
        - OLSR, batman-adv, etc.
    2 Advanced OS installations
        - LEDE-flashed routers (let's stop saying OpenWRT)
        - pfSense, Edge Routers, etc. 
    3 Be an ISP!
        - Running an IPv4 tunnel between two nodes
        - I know there is more here
    4 Running multiple instances of cjdroute on one machine, use all those cores!
