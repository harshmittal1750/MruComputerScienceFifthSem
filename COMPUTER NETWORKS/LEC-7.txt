An open system is a model that allows any two differnet systems to communicate regardless of their underlying
architecture.

OSI model is not a protocl, it is  a model for understanding and designing a n/w architecture that is flexible,
robust and interoperable.

ISO is the organization; OSI is the model.


OSI is a layered framework for the design of network systems that allows for communication across all types of computer
systems.

It consists of 7 separate but related layers, each of which defines a segment of th eprocess of moving info across
a network.

Physical Layer (Layer 1)
Data link layer (Layer 2)
Network Layer (Layer 3)
Transport Layer (Layer 4)
Session Layer (Layer 5)
Presenattion Layer (Layer 6)
Application Layer (LAyer 7)


Pneumonic for remembering the layers of OSI model:
Please do not touch Steve's Pet Alligator



Peer-to-peer processes ::
The processes on each machine that communicate at a given layer are called peer-to-peer processes.

the information at ecah layer is added in the form if headers and trailers (control data added to the beginning or end
of a data parcel)

Headers are added to the msg at layers 6,5,4,3 and 2
Trailers is added at layer 2.

at layer 1, the entire package is converted to a form that can be transferred to the receiving of machine.
At receiving end, the msg is unwrapped layer by Layer, with each process receiving and removing the data meant for it.

For ex: layer 2 removes the data meant for it, then passes the rest to layer 3.
Layer 3 removes the data meant for it and the passes the rest to layer 4 and so on.

Interface between Layers :

we need an interfcae between each pair of adjacent layers.
Each interface defines what info and services a layer must provide for the layer above it.
Well defined interfaces and layer functions provide modularity to the network.

Organization of the layers :
the seven layers can be thought of as belonging to 3 subgroups :

Layer 1,2,3 - physical, data link and network
are the network support layers; they dela with the physical aspects of moving data from one device to another(such as
electrical specifiactions, physical connections, physical addressing and transport timing, rleiability)

Layers 5,6,7- session, presenattion and application : user support layers
they allow interoperability among unrelated s/w systems

Layer 4: transport layer, ensures end-to end reliable data transmission while layer 2 ensures reliable transmisison
on a single link.

The upper OSI layers are always implemented in s/w. Lower layers are the combination of h/w and s/w, except for the 
physical layer, which is mostly hardware.

















































