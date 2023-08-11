# pootee
```
 -- pootee - version 1.0 --
Pootee is a command line ssh tool made my Tanner Kline. 
It can be controlled using command line arguments, or via user interface. 

command line usage:
  listing all connections
      pootee --action list
  resetting connection ids (reset to 0-N)
      pootee --action id
  adding a connection
      pootee --action add --connection asdf --ip 0.0.0.0 --username tanner --port 223 --tunnel 8890:localhost:8890
      - If port is not specified, default is used.
      - If tunnel is not specified, there will be no tunnel.
  deleting a connection
      pootee --action del --connection tbc2
      - You can also optionally use the connection id to delete
  connecting to connection
      pootee --action c --connection tbc2
      - You can also optionally use the connection id to connect
  connecting directly to system
      pootee --action c --ip 0.0.0.0 --username tanner --port 223 --tunnel 8890:localhost:8890
      - If port is not specified, default is used.
      - If tunnel is not specified, there will be no tunnel.
```