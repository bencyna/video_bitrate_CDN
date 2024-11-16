You should implement your proxy in this directory.

# Files 

## proxy
Proxy contains all the code for the proxy functionality. It includes setup of socket connections, connects to the dns server to find the ip addresses. Maintains client and server connections and forwards messages between them. It uses the manifest file for adpative bitrate as well. 

## dns_server
The DNS server file deals with dns record and listens and responds to dns queries using udp