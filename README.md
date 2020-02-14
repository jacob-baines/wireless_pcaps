# Wireless Pcap Repository

Wireless research and tool writing is often frustrated by the lack of real world data. What does a beacon from a Porsche look like? What extra tags does a Cisco Meraki include? Does a Fire Stick really have a zeroed out SSID? There are a million little questions like these, but its cost prohobitive to buy each one of these devices and test them. The researcher often needs to go out into the world, capture some data, and build off of their limited data set.

On the other hand, if other wardrivers are like me, data accumlated from wardrives is often lost or deleted because the data is of no practical use at the time of acquisition. This repository seeks to solve these two problems:

1. Preserve wardrive pcaps in a central location.
2. Provide researchers with real world datasets.

## Can I add a Pcap?

Yes, of course. I only ask the following:

1. Don't include any IP data. I think including lower layers (ARP, EAPOL, etc.) is fine, but storing raw ip data is probably asking for unwanted attention... and likely unnecessary for the stated purpose of this repository.
2. The pcap should include a couple thousand AP.
3. Break the pcap up into 99 MB-ish chunks.
4. Follow the directory structure / pcap naming scheme.

## What's with the directory structure?

Data is stored by region. Since I'm likely the only one to ever contribute, there will be a lot of us/<state> pcaps. The idea behind the structure, however, is that different ISP control different regions which leads to different sets of devices. Similarly, different products are popular in different regions. I don't know, there needed to be a structure and this made sense to me.
  
## GitHub isn't really meant for file storage...

k.

## License 
CC0 1.0 Universal
