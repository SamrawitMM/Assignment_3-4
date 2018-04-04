# Assignment_3-4
This program is written in c# language to preview DOS attack 
using client/server architecture.
Dos is an attack aganist a server sending many requests from the
client side that will make the services unavailable from functioning
efficiently. For instance, in linux , virtual box can act as the server 
and the current working os can act as the client.So
in this program, byte[] convert string package data 
to byte array, that is going to be sent to the end user.
Ip address and port is prompted so the user will insert ip 
and port respecively.
IPEndPoint specifies where the data is going to go to, using the
provided ip address(string ip address is 
parsed to ip address object)
Socket store the address family and the protocol type
udp, this socket allow us to send the data to the end point.
