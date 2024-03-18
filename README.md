# NETXII

### Installation Notes

* The firmware for this product is updated via the product's Web server. For detailed instructions, reference the [NET-X II User Manual](https://www.chauvetprofessional.com/wp-content/uploads/2018/01/Net-X_II_UM_Rev8_ML4.pdf).
* For users of products with serial number **LOWER THAN 09111455 – 0823-000001**, use firmware version 3.4
* For users of products with serial number **HIGHER THAN 09111455 – 0823-000001**, use firmware version 3.7

[V3.7 – NET-X II](https://github.com/Chauvet-Pro/NETXII/blob/36577126b6f7cd19b13cba70d56f40264566f1e3/firmware/V3.7_03-15-24.zip)
-	Improved performance to decrease output delay(s)

[V3.4 – NET-X II](https://github.com/Chauvet-Pro/NETXII/blob/36577126b6f7cd19b13cba70d56f40264566f1e3/firmware/V3.4_NET-X-II_Firmware_B1.0.zip)
-	Fixed bug that prevented seeing signal from console depending on boot order
-	Improved multi-console support with like manufacturers
-	Improved multi-console support with unlike manufacturers
-	Improved stability when operating on large networks >200 universes)

[V3.0 – NET-X II](https://github.com/Chauvet-Pro/OVATIONF55FC/blob/1c64c0d09b262975917ba32fe3e066897508be99/firmware/04-29-2021_Ovation%20F-55FC.zip)
-	Fixed bugs
-	Improved stability when switching between 1x8 and 2x4 splitter user modes
-	Improved synchronization timing when merging 2 DMX inputs
-	Improved synchronization timing when merging 1 DMX input and 1 network input (Art-Net or sACN)

[V2.7 – NET-X II](https://github.com/Chauvet-Pro/NETXII/blob/36577126b6f7cd19b13cba70d56f40264566f1e3/firmware/V2.7_NET-X_II_Firmware_beta.zip)
-	Fixed bugs that cause the following:
    * Whenever RDM discovery or get commands are sent via Art-RDM, the NET-X II freezes completely and must have the power reset.
    * Whenever multiple NET-X II’s are installed in a network, and 2 lighting controllers, if you open DMX Workshop via the Art-Poll (not RDM, yet), the NET-X II menu screen freezes up, and the menu is not accessible. Some/all of the ports will turn off their output.
    * Delayed response from pressing buttons on lighting controller to the light responding.
    * IGMP problems when using sACN protocols-sending to the wrong IP addresses from the Net-X II.
    * MAC address problems.
    * When the NET-X II crashes, you sometimes can reset the power and it will start working. However, sometimes, in some crashes, you need to remove the Ethernet signal from the lighting controller before resetting the power; then the NET-X II will start working. But, if you leave the Ethernet signal from the lighting controller plugged in while doing the power reset/reboot, the NET-X II will not start working.
    * When doing the changeover in multi-console mode (master/slave), the NET-X II does not know when to start listening from the new lighting controller (slave).

[V2.3 – NET-X II](https://github.com/Chauvet-Pro/NETXII/blob/36577126b6f7cd19b13cba70d56f40264566f1e3/firmware/V2.3_NET-X-II_Firmware_B1.0_released.zip)
-	Fixed bugs
-	Removed *Resend to Network* function
    * This also includes removing the “2nd Universe” menu item from the DMX ports menus. This decision was due to receiving multiple reports from customers that it was interfering with the network and causing conflicts when not properly configured, and that the configuration was not straightforward. 

[V1.9 – NET-X II](https://github.com/Chauvet-Pro/NETXII/blob/36577126b6f7cd19b13cba70d56f40264566f1e3/firmware/V1.9_NET-X-II_Firmware_B1.0_released.zip)
-	Fixed bugs
-	1x8 DMX Splitter Mode - solved input A versus input B capture

[V1.1 – NET-X II](https://github.com/Chauvet-Pro/NETXII/blob/36577126b6f7cd19b13cba70d56f40264566f1e3/firmware/V1.1_NET-X-II_Firmware_B1.0.zip)
-	Fixed a bug that causes universes to broadcast the wrong data that cannot be changed
-	Added stability improvements
