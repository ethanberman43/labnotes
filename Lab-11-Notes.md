#Lab 11 Notes
terminal commands m
- ping google.com: pings server (google.com is just readable address) 
- traceroute google.com: traces the route to the google server
- 	looks at each server that your computer contacts to reach the final destination you are looking for
-  ssh: can create a secure tunnel to a server, then request any information from that server and recieve information that may be blocked on the original server (ex: twitter in some countries)
-  ex: ssh -i /users/ethanberman/Downloads/EthansServer.pem
-  chmod g-rw to add/remove read/write permissions