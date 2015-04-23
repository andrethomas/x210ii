210ii is a Cortex-A8 development board designed for the SAMSUNG S5PV210 microcontroller, consists of the mother board, the MCU core circuit, and the touch screen LCD.

The product page where some information on the board can be viewed is located here:

http://www.wvshare.com/column/SAMSUNG_DevelopmentBoard.htm

The first change to the source code provided by the manufacturer relates to u-boot in making it use the external MMC socket (MMC1) for fastboot features. This allows the exclusive use of external MMC as opposed to on board inand/nand.

Updated sources are available here:
http://code.google.com/p/x210ii/source/browse/

The source code compiles correctly with the toolchain provided by the manufacturer which is on the DVD of your development board but can also be downloaded here:
http://code.google.com/p/x210ii/downloads/list