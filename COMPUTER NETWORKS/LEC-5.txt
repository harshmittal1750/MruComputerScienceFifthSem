Tree topology :

is a variation of star. 
not every device is connected to a central hub.
majority of devices connect to a secondary hub that in turn is connected to the central hub.

central hub in the tree is an active hub. An active hub contains a repeater, which is a h/w device that regenerate the
received bit patterns before sending them out.
Repeating strengthens transmissions and increases the distance a signal can travel.

Secondary hubs may be active or passive(provide a simple physical connection b/w the attached devices)

Advantages same as that of a star
1. It allows more device to be attached to a single central hub and it therefore increases the distance a signal can
travel b/w devices

2. It allows the network to isolate and priortize communications from different computers.

Example : Cable TV technology



Bus Topology :

Is Multipoint

one long cable acts as backbone to link all the devices in the .
Nodes are connected to the bus cable by drop lines(connection running b/w the device and the main cable) and 
taps(is a connector that either splices into the main cable or punctures the sheathing of a cable to create a contact
with he metallic core)

As a signal travels along the backbone, some of its energy is transformed into heat. therefore, it becomes weaker and 
weaker the farther it has to travel.
For thus reason, there is a limit on the mo. of taps a bus can support and on the distance b/w those taps.


Advantage :

1. Include ease of installation. (bus uses less cabling tahn mesh, star or tree)

Disadvantage :
Reconfiguration and fault isolation 
It can b difficult to add new devices; signal reflection at the taps can cause degradation in quality.
this degradation cn be controlled by limiting the no and spacing of devices connected to a given length of cable.
adding new devices may therefore require modifictaion or replacement of the backbone.

fault or break in the bus cable stops all transmission , even b.w devices on the same side of the problem
the damaged ares reflects signal back in the direction of origin, creating noise in both directions.

Ring Topology :

each device has dedicated p-t-p line configuration only with the 2 devices on either side of it.

A signal is passed along the ring in one direction, from device to device, until it reaches its destination.
each device in a ring incorporates a Repeater.
When a devices receives a signal intended for another device, its repeater regenerates the bits and passes them along.

Easy to install and reconfigure. 
only constarints Media and traffic consideration(maximum ring length and no. of devices)

Fault isolation is simplified. 
Generally ina ring, signal is circulating all the times. If one device does not receive a signal within a specified
period, it can issue an alarm. this alrm alerts the n/w operator to the problem and its loaction.

Disadvantage :

Unidirectioanl traffic
In a simple ring, a break in the ring can disable the entire network.
this weakness can be solved by using a dual ring or a switch capable of closing off the break.


Hybrid Topologies :
often a n/w combines several topologies as subnetwork linked together in a larger topology.















































































