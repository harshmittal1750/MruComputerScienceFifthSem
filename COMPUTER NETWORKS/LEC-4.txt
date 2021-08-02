Topology : (defines the physical or logical arrangement of links in a network)

 refers to the  way a network is laid out, either physically or logically.

Two or more devices connect to a link; two or more links form a topology.
is the geometric represnetation representation of the relationship of all the lniks and linking 
devices(node) to each other.

5 basic topology

Mesh
Star
Tree
Bus
and Ring

these 5 labels describe how the devices in an network ar einterconnected rather than their physical
arrangement.

For ex: having a star topology doesnt mean that all computers in the network must be placed physically
around a hub in a star shape.

2 relationshipr r possible : 
peer-to-peer (where the devices share the link equally) :: Ring and mesh topologies r more convenient
Primary-secondary(where one device controls traffic and the others must transmit through it) star and tree are more 
convenient
A bus topology is equally convenient for either.

Mesh topology :

Every device has a dedicated(link carries traffic only b/w the two device it connects)
 p-t-p(point-to-point) link to every other device.
a fully connected mesh n/w therefore has n * (n-1) / 2 physical channels to link n devices.

To accommodate tht many links, every device on the n/w must have n-1 I/O ports.
Advantages :
1. the use of dedicated link guarantees that each connection can carry itw own data, eliminating the traffic problem
that can occur whne links must be shared by multiple devices.

2. Mesh topology is robust. If one link becomes unusable, it does not incapacitate the entire system.

3. Privacy and security, when every msg tarvles along a dedicated line, only the intended receiver sees it. 
Physical boundaries prevent other users from gaining access to msgs.

4. p-t-p links make fault identification and fault isolation easy. Traffic can be routed to avoid links with suspected 
problems. this facility enables the n.w manager to discover precise location of the fault and aids in finding its cause 
and solution.

Disadvantages :
1. Amount of cabling and the no. of I/O ports required
bcoz every device must be connected to every other device, installation and reconfiguration are difficult.

2. the sheer bulk of the wiring can be greater than the available space (in walls, floors, ceilinf) can accomodate.

3. the h/w required to connect each link (I/O ports and cable) can be prohibitively expensive.

For ex: As a backbone connecting the main computers of a hybrid n.w that can include several other topologies.


Star Topology :


Each device has a dedicated p-t-p link only to a central controller, usually called a HUB. the devices r not directly linked to each other.

unlike mesh topology, a star topology does not allow direct traffic b/w devices. the controller acts an an exchange:
if one devices wants to send data to another; it sends the data to the controller, which then relays the data to the 
other connected device.

A star topology is less expensive than mesh. 
each device needs only one link and one I/O port to connect it to any no of others. Hence, easy to install and 
reconfigure.
Far less cabling needs to be housed and addition, moves, and deletions involve one connection; b/w that device and the 
hub.


Robustness : if one link fails, only that link is affected. all other links remains active.
Easy fault identification and fault isolation. As long as the hub is working, it can be used link problems
and bypass defective links.

tree, ring, bus(more cabling is required in star)

Disadvantage : If hub fails







































































