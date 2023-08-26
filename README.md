# TFCAB01 - ThunderFly Pixhawk compatible cabling system

TFCABxxyy01 are silicone cables for [Pixhawk](https://pixhawk.org/) based drones. The cables are equipped on both sides with JST-GH high-strength plastic clips, which feature a locking mechanism for good mechanical connection and resistance to vibrations. Cables are designed and manufactured to have increased resistance to electromagnetic interference and self cross-talk.

![](https://user-images.githubusercontent.com/5196729/234793444-a4d4c73b-5eb9-4614-a92b-722d95fa6c30.jpg)

## Where I can buy them?
<a href="https://www.tindie.com/stores/thunderfly/"><img src="https://d2ss6ovg47m0r5.cloudfront.net/badges/tindie-mediums.png" alt="I sell on Tindie" width="150" height="78" align="right"></a>

Cables can be purchased online from Thunderfly [Tindie store](https://www.tindie.com/stores/thunderfly/) or contact ThunderFly team by email info@thunderfly.cz for individual quotation. Links to individual variants can be found in the following list.

## List of ThunderFly cables

Currently, there are available cables mainly for I²C and UAVCAN busses, although [more cable variants are defined](https://docs.px4.io/main/en/assembly/cable_wiring.html). That less common variants of cables could be delivered upon request. 

 * TFCAB15I2C01 (I2C, 15cm), [buy it online](https://www.tindie.com/products/30113/)
 * TFCAB30I2C01 (I2C, 30cm), [buy it online](https://www.tindie.com/products/30113/)
 * TFCAB45I2C01 (I2C, 45cm), [buy it online](https://www.tindie.com/products/30113/)
 * TFCAB15CAN01 (CAN, 15cm)
 * TFCAB30CAN01 (CAN, 30cm)
 * TFCAB45CAN01 (CAN, 45cm)

### Wires

 * Insulation: Silicone, high temperature resistant (up to 200 °C)
 * Wire outer diameter: 1mm
 * Conductor: 26 AWG;  20/0.08, Sn plated Cu
 * Wire ending: JST-GH

### Plastic endings
We use original JST-GH connectors from the manufacturer JST  (JAPAN SOLDERLESS TERMINALS).

## Color scheme

For easy orientation in avionics cabling cables we have designed a  ThunderFly color scheme.  The each type of signal/cable has own color combination, which is common in all our equipment.


## I2C bus

|Signal | Pixhawk Color | ThunderFly color |
|--------|------------------|---------------------|
| +5V  | Red             |   ![red](https://user-images.githubusercontent.com/5196729/102204855-ab1c3300-3eca-11eb-8083-646d633e3aef.png) Red                   |
| SCL  | Black          |  ![yellow](https://user-images.githubusercontent.com/5196729/102204908-bc653f80-3eca-11eb-9a1d-a02ea5481c03.png) Yellow                |
| SDA  | Black          |  ![green](https://user-images.githubusercontent.com/5196729/102205114-04846200-3ecb-11eb-8eb8-251c7e564707.png) Green                |
| GND | Black          | ![black](https://user-images.githubusercontent.com/5196729/102204896-b8d1b880-3eca-11eb-8b73-656cac9104e4.png) Black                 |


![ThunderFly I2C JST-GH connection cable](doc/img/jstgh_i2c.jpg)



#### Cable twisting

- 10 turns for each pair  SCL/+5V and SDA/GND per 30cm cable length
- 4 turns of both pairs together per 30cm cable length.


## UAVCAN bus

|Signal | Pixhawk Color | ThunderFly color |
|--------|------------------|---------------------|
| +5V  |        Red       | ![red](https://user-images.githubusercontent.com/5196729/102204855-ab1c3300-3eca-11eb-8083-646d633e3aef.png) Red                 |
| CAN_H  |  Black     | ![white](https://user-images.githubusercontent.com/5196729/102204632-5e385c80-3eca-11eb-985d-a881acfae26a.png) White              |
| CAN_L |    Black     | ![yellow](https://user-images.githubusercontent.com/5196729/102204908-bc653f80-3eca-11eb-9a1d-a02ea5481c03.png) Yellow             |
| GND |        Black    | ![black](https://user-images.githubusercontent.com/5196729/102204896-b8d1b880-3eca-11eb-8b73-656cac9104e4.png) Black               |


![ThunderFly CAN JST-GH connection cable](doc/img/jstgh_CAN.jpg)


#### Cable twisting
- 10 turns for each pair GND/+5V and CAN_L/CAN_H per 30cm cable length
- 4 turns of both pairs together per 30cm cable length.
