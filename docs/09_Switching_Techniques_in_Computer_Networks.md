# 09 - Switching Techniques in Computer Networks


Switching 
switching in computer network help in deciding the best route for data transmission if there are multiple path in a larger network

one to one connection

switching techniques
circuit switching
message switching
packet switching


1: circuit switching:
a path dedicated path is established between the sender and reciver
before data transfar conection will be established first
example telephone network

3 phases in circuit switching
1. connection establishment
2. data transfar
3. connection disconnection


2: message switching
store and forword mechanisam
message is transfarred as a complete unit and forword using store and forword mechinasam at the intermediary node.
not suited for streaming media and real time applications.


3: Packet Switching
the internet is a packet switched network
message is broken in indivudial chunks called as packet
each packet is sent individully
each packet will have source and destination ip addrss with sequance number.
sequance number will help the reciver to
recordor the packets.
ditect missing packets 
send acknowladgements

two approach in oacket switching
1. datagram approach
2. virtual circuit approach


1: datagram packet switching is also known as conncetionless  switching 
each indenpenditly entity is called as datagram
datargrams contain destination information and the intermidery devices uses this information to forword datagrams to right destination
in datagram pacets the switching approach the path is not fixed
intermdiates notes take the routing descision to forword the packets.


2: virtual cerciute approach:
virtual ciruit switching is also known as conection orianted switching
in the case of virtual circuit switching a preplamned rout is establishing before the message are set
call request and call accept packet are sue to establish the connection between sender and reciver
in this approach the path is fixed for the durationn of a logical connection