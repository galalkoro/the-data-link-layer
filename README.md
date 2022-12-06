# The data link layer

The data link layer of the OSI model (Layer 2), as shown in the figure, prepares network data for the physical network. The data link layer is responsible for network interface card (NIC) to network interface card communications.

## What the data link does:

- Enabels upper layer to access the media.
- Accept data, usually Layer 3 packets IPv4 or IPv6 and encapsulates them into Layer 2 frames.
- Controls how data is placed and recieved on the media.
- Exchange frames between endpoints over the network media.
- Receives encapsulated data, usually Layer 3 packets, and directs them to the proper upper-layer protocol.
- Performs error detection and rejects any corrapt frame.

![the figur](network-images-figure/the-data-link-layer.png)
