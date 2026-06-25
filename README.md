 # Custom-Computer

 This is a fully custom laptop that is built around a Lattepanda Mu, which is a computer module that is credit card-sized. This project took around two to three and a half months. This project is inspired by Ben Makes Everything and Bryan. The specific video that Ben Makes Everything that I used is "https://www.youtube.com/watch?v=o00P7wHbd2c," and the video that Bryan that I used is "https://www.youtube.com/watch?v=fks3PBodyiE." Bryan's website is "https://www.byran.ee/" 

 Below is an image of the full shell of the custom laptop without the hinge mechanism and the internal components.

------------------------------------------------------------------------------------------------------------------------------------------
<img width="703" height="475" alt="Screen Shot 2026-06-09 at 8 22 35 PM" src="https://github.com/user-attachments/assets/536cf32c-d19b-49a7-a1ec-af2e29deac9f" />

Configuration of the Lattepanda Mu,
  The exact size of the Lattepanda Mu is 69.6MM by 60MM, and the standard credit card is 85.6MM by 54MM it is very. The Lattepanda Mu has an  Intel X86 chip. It can be configured with an   N100  or an  N305 chip.  The ram that on the Lattepanda Mu is 16GB of LPDDR5 4800MT/s, and for storage, it can be equipped with an M.2 2230 NVME SSD or slash and a 64GB eMMC 5.1 Storage. And of course it has a wifi card, so you can have wifi. 

Configuration of the Lattepanda Mu,
The configuration of the full device is shown below as an image.
------------------------------------------------------------------------------------------------------------------------------------------
<img width="486" height="346" alt="Block Diagram" src="https://github.com/user-attachments/assets/ce8881e0-13f9-46da-8593-4cbd965ed5e8" />

The Keyboard,
  The keyboard is a split Ortholinear keyboard because Ortholinear keyboards are easier and more natural to use. The keyboard is a fork of  Ben Makes Everything's first keyboard from his video "Building a LattePanda Mu Cyberdeck." The link to his video is https://www.youtube.com/watch?v=o00P7wHbd2c, and the time that the Ortholinear keyboard is mentioned is between the time 5:10 to 8:45. 

The Trackpad,
 The trackpad is made by the company Azoteq, and the exact trackpad that I use is the PXM0091. Azoteq says them selses "The IQS9150 is a generic and configurable trackpad device aimed to be suitable for numerous design variations and requirements. The PXM0091 utilizes the IQS9150 to provide high-performance multitouch (linearity, accuracy, low-noise) trackpad outputs, switch input, and an on-chip gesture recognition engine. The website that I got it from was "https://seltech-intl.com/datasheets/pxm0091.pdf." 

The port on the Laptop,
  The laptop has four USB ports in the style of a Raspberry Pi. The HDMI port is on the back, like some gaming laptops, such as the HP OMEN MAX 16. There are a few internal USB ports, but not use the traditional ribbon connectors and cables; instead, it is using a JST connector, and there is an internal amp on the mainboard, but the BIOS and  Lattepanda Mu software do not support I2S.  Lattepanda said, "They will support I2S in the near future." So I decided to use a USB to audio using a rapberry pi pico to I2S, then I2S to a  USB audio converter, then to the speaker. 

The Power System
  The power button is on the main board, and it is internal, but the reason why is that when testing it, you don't need to go to the side of the laptop. But how to turn on the computer, you may ask. There is a keyboard switch on the side of the computer that is wired to the internal power button. All so there is a switch that connects directly to the battery and skips the main board and all of the software, so in an emergency, you canan switch it, and all power is shut off immediately  The battery is a 18650 4S5P battery pacl connected to an trusted AliExpress BMS, which is the  "140W 2S 3S 4S 5S 6S Lithium Battery Charging Board Bidirectional Fast Charging Li-ion Lifepo4 BMS Charger Type-C IP2366 PD3.1". Which is then connected to a 100A ANL fuse. Then it goes to a screw terminal and connects to the main board with another screw terminal, which takes the 9-12 volts from the battery. 

Battery Life of the laptop
  Battery life is a key thing when using a laptop. When you have a small battery, you have a little time on the battery, and when you have a big battery, your batter last a long time. The battery life is about 7 hours on high-performance mode, 10 hours on balanced mode, and on battery saver mode, it lasts about 15 hours. These numbers are done by math but not tested in the real world. The amount of watt hours that the battery is 120-176 watt hours. The legal limit that laptops can go on planed are 99.99 watt hours, and for battery banks is 120-176. So if you decide to make this laptop, you can't bring it on a plane, so you have to send it to the location.

