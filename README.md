# SAMA7D65 System-On-Modules Series
## Early Access Repository

The Microchip SAMA7D65 System-On-Module Series is a small, single-sided SOM series based on a System-in-Package (SiP) Arm® Cortex®-A7 CPU-based embedded microprocessor running up to 1 GHz.
The SAMA7D65 SOM Series is built on a common set of proven Microchip components to reduce time to market by simplifying hardware design and software development.
The SOM embeds a SAMA7D65 SiP microprocessor with up to 2-Gbit DDR SDRAM, up to 8-Gbit NAND Flash memory, a Gigabit Ethernet PHY, a 64-Mbit serial Quad I/O Flash memory and a dedicated Power Management Unit.
The SAMA7D65 SOM Series also limits the design rules of the main application board, reducing overall PCB complexity and cost. The SAMA7D65 SOM Series is supported by a free Linux® distribution and bare-metal C examples.   

This new SOM series is targeted for production very soon, but in the meantime this Github repository serves as the main resource for documentation and software support for the SAMA7D65 SOM series.  Samples are available today, please contact your local Microchip sales office. 

For more information about the SAMA7D65 CPU, or the associated SIPs referenced above, please visit the respective product page on Microchip.com.
* https://www.microchip.com/en-us/product/SAMA7D65


<p align="center"><img src="SAMA7D65-SOM.jpg" /></p>


## Collaterals
* Hardware
  * SOM Hardware Design Files can be requested by contacting your local [Microchip Sales or Sales representative](https://www.microchip.com/en-us/about/global-sales-and-distribution)
* Documentation
  * [SAMA7D65 SOM Series Preliminary Data Sheet](Documentation/)
  * [System-On-Module (SOM) Assembly and Storage Guidelines](https://ww1.microchip.com/downloads/aemDocuments/documents/MPU32/ApplicationNotes/ApplicationNotes/System-On-Module-SOM-Assembly-and-Storage-Guidelines-DS00005249.pdf)
  * [System-On-Module (SOM) Pick and Place Guidelines](https://ww1.microchip.com/downloads/aemDocuments/documents/MPU32/ApplicationNotes/ApplicationNotes/System-On-Module-SOM-Pick-and-Place-Guidelines-ds00004878.pdf)
* Software
  * [Linux Solution](http://www.linux4sam.org/)
  * [MPLAB Harmony v3 Solution](https://www.microchip.com/en-us/tools-resources/configure/mplab-harmony)
  * [MPLAB Discover Code examples](https://mplab-discover.microchip.com/v2/category/com.microchip.code.examples?dsl=sama7d65)
* Tools
  * [SAM-BA Programming Tool](https://github.com/atmelcorp/sam-ba/releases/tag/v3.9)
  * [MPLAB X Integrated Development Environment](https://www.microchip.com/en-us/tools-resources/develop/mplab-x-ide)

## Hardware and Software recommendations:
* Hardware
  * Since the assembly recipe is not yet fully qualified, we recommend, for the moment, to solder the System-On-Module on the mother board manually.
* Software
  * NAND-Flash: Configure each pin of the NAND flash data bus in Drive Strength “Type A” mode.

