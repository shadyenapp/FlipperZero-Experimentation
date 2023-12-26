# RFID Projects

## RFID Card Technology
RFID technology uses radio waves across a one and two way channel [[1]](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8471504/). RFID readers and tags use different algorithms of modulation, typically the ASK, PSK, and QAM. 
### ASK Cards

### PSK Cards

## Animal Tags
Microchips inside pets and animals used to identify them and their owners are used as RFID with the FDX-B protocol. The FDX-B protocol transmits 15 Hex digits at 134.2 Khz, as set by the ISO 11784 and 11785. While I have not found any documentation determining which modulation algorithm the FDX-B protocol uses, my Flipper could read my cat's tag using the ASK modulation. 
Upon reading the data from the cat's microchip, the Flipper will show the hex bits recieved, as well as the ID of the tag. 
