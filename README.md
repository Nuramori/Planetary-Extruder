# Planetary Extruder for the BLV Cube - The EdP-Drive.

<B><a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.</B>


This is an extruder design specifically for the BLV Cube, with a branch modified for the BLV metal carrier upgrade.  Key design concepts that drove the design direction were the following:

Implement a geared reduction drive to allow for a smaller and lighter stepper motor, that offsets the motor's lower torque with the torque increase of a planetary drive system, combined with a helical gear ratio to reach a final ratio of 12:1

Utilize a BLTouch as the z-axis prober.

Allow for multiple hotend types by basing attachments via a simple adapter plate and parts cooler nozzle change.  Allow swaps with a couple of screws/bolts.

Electronics support to be integrated into the shell carrier.

A future release will be more universal with a blank backplate for modification to adapt to other carrier/printer needs.

If you wish to look around in a web browser, here are some links.

Integrated Version : https://a360.co/2Vma0a4<BR>
Metal/universal version : https://a360.co/36IUueP
<br>
  
  
# UPDATE v1.04 [March 6, 2021]

Thanks to a fellow BLV owner that's building a metal carrier version with the toolboard, there was an additional tweak necessary if people were to use the experimental belt retainers that come with the metal kit.  It also needed fixing... 

I still plan on doing another update that has the installation/construction sequence to make it easier for people to assemble the extruder.
<br>
<br>


# UPDATE v1.03 [March 4, 2021]

Thanks to a fellow BLV owner that's building a metal carrier version with the toolboard, I found a few errors that needed fixing... 
<br>
<br>


# UPDATE v1.02 [March 3, 2021]

Added a new blower frame for the metal carrier to accommodate the Duet Toolboard up to board version 1.0 (current as of this update).
<br>
<br>


# UPDATE v1.01 [January 14, 2021]

I added new adapters; one specifically for the for the metal carrier variation, to accommodate the Mosquito (air-cooled) and the other for the Dragon hotend from TriangleLabs.  The Dragon Adapter is complete for both the integrated and metal carriers.

I plan on doing an update soon that has the installation/construction sequence to make it easier for people to assemble things :p.
<br>
<br>


# FIRST RELEASE v1.0 [Dec 25, 2020]

The project has been printed and tested, with a few minor tweaks.  I'm formally calling it the EdP-Drive, or "P-Drive" if you wish.  I also have released this under a new licensing terms, to allow for community development, and open to commercial USE.  I would as anyone that utilizes this design, extend the courtesy of proper credits for the work and expense put into bringing this work to the community.  Thanks.


<B>Non-Printed Parts List</B>

<B>Extruder Motor</B><BR>
<B>Type&emsp;&emsp;&emsp;&ensp;&ensp;Manufacturer&emsp;&emsp;&ensp;&ensp;Part No.</B>          
NEMA11&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Moons Industries&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;MS11HS1P4100   

<B>Source :</B>     Moons Industries<BR>
<B>Link :</B>       https://www.moonsindustries.com/p/nema-11-standard-hybrid-stepper-motors/ms11hs1p4100-000004611110015846<BR><BR>

<B>Bearings<BR>
Type&emsp;&emsp;&emsp;&emsp;Quantity&emsp;&emsp;Use/Purpose</B>                   
B695ZZ&emsp;&emsp;&nbsp;&nbsp;one (1)&emsp;&emsp;&emsp;&ensp;Motor spindle support<BR>
B676ZZ&emsp;&emsp;&nbsp;&nbsp;three (3)&emsp;&emsp;&emsp;Planetary gears<BR>
MR148ZZ&emsp;&nbsp;&nbsp;&nbsp;three (3)&emsp;&emsp;&nbsp;&nbsp;&nbsp;Planetary carrier and driven sun gear drive support<BR>

<B>Source :     Misumi, Amazon</B><BR>
<B>Misumi :</B>&emsp;https://us.misumi-ec.com/vona2/detail/110300107560/?HissuCode=B695ZZ&PNSearch=B695ZZ&searchFlow=results2type&KWSearch=B695zz<BR>
<B>Misumi :</B>&emsp;https://us.misumi-ec.com/vona2/detail/110300107560/?HissuCode=B676ZZ&PNSearch=B676ZZ&searchFlow=results2type&KWSearch=B676ZZ<BR>
<B>Amazon :</B>&emsp;https://www.amazon.com/uxcell-MR148ZZ-Groove-Bearings-Shielded/dp/B082PPPSPT/ref=sr_1_3?dchild=1&keywords=MR148zz&qid=1606114609&sr=8-3<BR><BR>

<B>Hobbed Gears<BR>
Type&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&nbsp;Quantity&emsp;&emsp;&emsp;Detail</B><BR>
BondTech Drive Gears&emsp;&emsp;one (1)&emsp;&emsp;&emsp;&nbsp;&nbsp;1.75mm Filament, 8mm Shaft size

Source :     Filastruder<BR>
Link :       https://www.filastruder.com/collections/bondtech/products/drivegear-kit?variant=12119193124935
<BR><BR>


<B>Clamp Thumbscrew Tensioner<BR>
Type&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&nbsp;Quantity&emsp;&emsp;&emsp;</B><BR>
BondTech Thumbscrew Tensioner&emsp;&emsp;&emsp;one (1)&emsp;&emsp;&emsp;&nbsp;&nbsp;

Source :     Filastruder<BR>
Link :       https://www.filastruder.com/collections/bondtech/products/bondtech-thumbscrew-assembly
<BR>
<BR>  


<B>Optical Endstop</B><BR>
Type&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&nbsp;Quantity&emsp;&emsp;&emsp;Manufacturer</B><BR>
Optical      one (1)       Lerdge

Source:      Amazon
Link:        https://www.amazon.com/Printer-Accessories-Optical-Tachometer-Photoelectric/dp/B088P3TPCB
alternate:   https://www.amazon.com/MakerHawk-Optical-Endstop-Photoelectric-Control/dp/B07PMW2QMT/ref=sr_1_2?dchild=1&keywords=large+end+stop+optical&qid=1606115247&s=industrial&sr=1-2
<BR>
<BR>  
  
<B>Fan</B><BR>
Type&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&nbsp;Quantity&emsp;&emsp;&emsp;Detail</B><BR>
5015         one (1)    12v Dual ball bearing

Source :     Amazon
Link :       https://www.amazon.com/WINSINN-Bearing-50x15mm-Turbine-Brushless/dp/B07WFJV28K/ref=sr_1_5?dchild=1&keywords=5015+winsinn&qid=1606120419&refinements=p_85%3A2470955011&rnid=2470954011&rps=1&sr=8-5<BR><BR>

<B>BLTouch offset values for listed adapters:</B><BR>
The default x,y offsets are x=-25, y=0 unless noted otherwise.<BR>

<B>Current adaptors using this default are as follows:</B><BR>
Slice Engineering Mosquito standard<BR>
Slice Engineering Copperhead<BR>
E3D V6<BR>
Nova<BR>
  
<B>Unique offsets are as follows:</B><BR>
Mosquito Liquid :&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;x=0, y=-20<BR><BR>
  
<B>Configuring steps/mm</B><BR>  
Since the extruder utilizes gear reduction to 12:1 to increase torque, the steps/mm need to be adjusted.  <B>Based on a 0.8degree motor, it is recommended the base value be set to 1299.</B><BR>

The standard method of calibrating extruder steps is recommended to fine tune this value to suit your machine.
