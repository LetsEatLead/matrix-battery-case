# matrix-battery-case
This is a case for the esp32-s3 Matrix board made by waveshare which includes a battery, a battery charger, and a switch. 

<img src="media/Assembled Photo.JPG" alt="(Image of the case fully assembled)" width="500">

# Materials:
1x Waveshare esp32-s3 Matrix

1x 802525 Lipo battery with 

1x Corresponding connector for lipo battery 

1x SS-12D00 (1P2T) slide switch

1x Usb C adjustable lipo charger (This unit can be found online, particularly on aliexpress using the keywords :Usb C, Adjustable, Mini, Lipo Charger. An image is attached) 

<img src="media/Battery Charger.png" alt="(Image of the battery charger)" width="300">

#Wiring
Batt Connector + --> Batt Charger +

Batt Connector - --> Batt Charger B-

Batt Charger + --> Switch Terminal A

Batt Charger o- --> Matrix Ground

Switch Terminal B --> Matrix 5v 

#Printing Considerations and Assembly
Please print this using a 0.4mm nozzle and at least a layer height of 0.16mm fine. If you use a more granular layer height there may be issues with floating layers. 

When wiring, keep your wire runs on the shorter side, I utilized super glue to hold the switch in place. Consult the images for more detailed assembly. 

<img src="media/Internal Organization.JPG" alt="(Image of the internal assembly)" width="500">
<img src="media/Internal Organization Expanded.JPG" alt="(Image of the internal assembly)" width="500">

#Extra Notes
Printables Link:

Big thanks to Vateva for creating this awesome fluid simulator for this devboard, which actually inspired this prokect. Heres a link to their repo: https://github.com/Vateva/Esp32FluidSimulation8x8 
