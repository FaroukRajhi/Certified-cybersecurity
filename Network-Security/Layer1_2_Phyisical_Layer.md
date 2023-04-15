### Layer 1 - Physical layer

* Hardware

- Cabling and network cards
- Two devices: hubs and repeaters

* Traffic

- No intelligence, Filtering or stopping
- Receives  traffic on one port, amplifies the signal and send it on to any other ports
- Bits encoded as some from of signal.

* Hardware Limitations

- Attenuation - strength in electrical signal in the wire starts to weaken. It degrade over distance.
- Network design - hubs forward all traffic to all ports, inefficient way of operating.

# Layer 2 - Data Link Layer

* Hardware

- Switches and bridges (2 port switch)
- Receives traffic on one connection and sends to another.

* Addresses

- Burned in address assigned by manufacturer
- Media Access Control (MAC) address
  48 bits long:
     24 bits identified by the manufacturer and can override
     Last 24 bits unique number for individual network interfaces

* Traffic

- Switches/Bridges can read the destination (to) and source (from) addresses
- Frames have device address of sender and the intended recipient


* Filtering

- Not sending all traffic to everybody, less noisy and more efficient
- Leaves other ports to do their own thing

* Spoofing

- Attackers can change the MAC address.
- Confuses the switch sufficiently that the traffic is is redirected.
- Impersonate a device and receives their traffic.