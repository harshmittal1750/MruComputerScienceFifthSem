 
 Network Layer :

Whereas the DLL oversees the delivery of the packet between 2 systems on the same network(links), the
network layer ensures that each packet gets from its point of origin to its final destination.

If 2 systems are connected to the same link, there is usually no need for a network layer.
However if 2 systems are attched to different n/ws(links) with connecting devices between the n/ws
(links), there is often a need for the network layer to accomplish source-t-destination delivery.

Logical addressing :
The physical addressing implemented by the DLL handles the addressing problem locally. 
If a packet passes the network boundary, we need another addressing system to help distinguish the 
source and destination systems. 
The network layer adds a header to the packet coming from the upper layer that, among other things
include logical address of the sender and receiver.


Routing :
When independent n/ws or links are connected together to create an internetwork(a n/w of n/ws) or a 
large network, the connceting devices (called routers or gateways) route the packets to their final
destination.
One of the functions of the n/w layer is to provide this mechanism.


Transport Layer :
whereas the network layer oversees end-to-end delivery of individual packets, it does not recognize any relationship
between those packets.
It treats each one independently, as though each piece belonged to a separate message, whether o rnot it does.

the transport layer on the other hand ensures that the whole message arrives intact and in order, overseeing both
error control and flow control at the source-to-destination level.

Service-point addressing :
Computers often run several pgms at the same time. For this reason, s-t-d delivery means delivery not only from
one computer to the next but also from a specific process(running pgm) on one computer to a specific process(running
pgm) on the other.

The transport layer header therefore must include a type of address called a service-point address (or port address).
The network layer gets each packet to the correct computer; the transport layer gets the entire msg to the correct
process on that computer.

Segmentation and Reassembly :
A msg is divided into transmittable segments, each segment containing a sequence number.
these numbers enable the transport layer to reassemble the msgs correctly upon arriving at the destination and to identify
and replace packets that were lost in the transmission.

Connection control :
The transport layer can be either connectionless or connection oriented. 
A connectionless transport layer treats each segment as an independent packet and delivers it to the transport layer 
at the destination machine.
A connection oriented transport layer makes a connection with the transport layer at the destination m/c before
delivering the packets. 
After all the data is transferred the connection is terminated.

Flow Control :
Like DLL, the transport layer is responsible for flow control.
However, the flow control at this layer is performed end to end rather than across a single link.

Error Control :
Like DLL, the transport layer is responsible for error control. 
However error control at this layer is performed end to end rather than across a single link.
The sending transport layer makes sure that the entire msg arrives at the reciving transport layer without error (damage
, loss, or duplication)
Error correction is usuaaly achieved through re transmission.


Session Layer

Dialog Control : The session layer allows two systems too enter into a dialog.
It allows the communication between two processes to tak eplace either ina half duplex (one way at a time) or full duplex
(two ways at a time).
For ex the dialog between a terminal connected to a mainframe can be half duplex.
 

Synchronization :  the session layer allows a process to add checkpts (sync points) into a stream of data.
For ex, if  a system is sending a file of 2000 pages, it is advisable to insert checkpts after every 100 pages to ensure
tht each 100 page until it is received and acknowledged independently.
In this case if a crash happens during the transmission of page 523, retransmission begins at page 501; pages 1-500 need not
be retansmitted.

Presentation layer

Translation : The processes in two systems are usually exchangig info in the form of character strings, numbers and so on.
The information should be changed to bit streams before being transmitted.

The presentation layer at the sender changes the infor from its sender dependant format into a common format.
The presentation layer at the receiving machine changes the common format into its receiver dependant format.

Encryption : To carry sensitive info, a systme must be abl eto assure privacy,
Encryption means that the sender transforms the original info to another form and sends the resulting msg out over the
n/w.
Decrption reverses the original process to transform the msg back to its original form.


Compression : Data compression reduces the no of bits to be transmitted. This becomes important in the transmission of 
multimedia such as text, audion and video.



Application Layer :

Network Virtual Terminal
is a software version of a physical temrinal and allows a user to log  onto a remote host.

To do so, the application creates a s/w emulation of a terminal at the remote host. 
The user's computer talks to the s/w terminal, which in turn talks to the host and vice versa. 
The remote host beliwves it is communicating with one of its own terminals and allows you to log on.

File transfer , access and management(FTAM) :
This application allows a user to access files in a remote computer(to make changes or read data), to retrive files
from a remote computer, and to manage or control files in a remote computer.

Mail Services :
this application provides the basis for e-mail forwarding and storage

Directory Services :
This application provides ditributed database sources and access for global information about various objects and services.


































































































