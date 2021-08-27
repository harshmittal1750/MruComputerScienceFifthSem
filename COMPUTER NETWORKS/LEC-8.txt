Physical Layer :


It coordinates the functions required to transmit a bit stream over a physical medium.
Id deals with mecahnical and electrical specifications of the interface and transmission medium.
It also defines the procedures and functions that physical devices and interfaces have to perform for transmission to
occur.

1. Physical characteristics of interfaces and media : 
defines characteristics of the interfaces b/w the devices and the transmission medium
also it defines the type of transmission medium

2. Representation of bits : to be transmited bits must be encoded into signals-electrical or optical.
The physical layer defines the type of encoding(how 0s and 1s are changed to signals)

3. Data Rate : transmission rate- no of bits sent each second-is alos defined by physical layer. 
define sthe duration of a bit, which is how long it lasts.

4. Synchronization of bits : the sender and receiber must be synchronized at the bit level.
clocks must be synchronized

5. Line configuration : phy layr is concerned with the connection of devices to the medium.
In p-t-p configuartion, 2 devices are connected together through a dedicated link.
In multipt config, a link is shared b/w several devices.

6. Physical topology : how devices r connected to make a network. [mesh, star, tree, ring, bus]

7. Transmission mode : the physical layer also defines the direction os transmission b/w 2 devices:
Simplex
Half Duplex
Full Duplex

Data Link Layer
transforms the physical layer, a raw transmission facility, to a relaible link and is responsible for node-to-node
delivery.
It makes the physicla layer appear error free to the upper layer(Network LAyer)

Specific responsibilities of DLL :

1. Framing : DLL divided the stream of bits received from the n/w layer into manageable data units are frames.

2. Physical Addressing : If frames are to b distributed to diff systems on th en/w, the DLL adds a header to the frame to 
define the physical address of the sender(source address) an dor reciever(destination address) of the frame.
if frame is intended for a sytem outside the senders network the reciver address is the address of the device that connect 
one n/w to the next.

3. Flow control :if the rate at which data are absorbed by the receiver is less than the rate produced in the sender,
the DLL imposes a flow control mechnanism to prevent overwhelming the receiver.

4. Error control : DLL adds reliability to the physical layer by adding mechnanisms to detect and retransmit damages or
lost frames.
It also uses amechnaism to prevent duplication of frames.
Error control is normally achieved through a trailer added to the end of the frame.

5. Access control : when two or more devices are connected to the same link, DLL protocols are necessary to determine
which device has control over the link at any given time.





































