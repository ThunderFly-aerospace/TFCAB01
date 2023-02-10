# TFCAB01
TFCABxxyy01 are silicone cables for PixHawk based drones. Cables are from booth side equipted with JST-GH plastic endings. Cables are designed and manufactured to have increased restistance to electromagnetic interference and cross-talk.


## List of ThunderFly cables

 * TFCAB15I2C01 (I2C, 15cm)
 * TFCAB30I2C01 (I2C, 30cm)
 * TFCAB45I2C01 (I2C, 45cm)
 * TFCAB15CAN01 (CAN, 15cm)
 * TFCAB30CAN01 (CAN, 30cm)
 * TFCAB45CAN01 (CAN, 45cm)

### Wires
 * Insulation: Silicone, high temperature resistant (up to 200C)
 * Wire outer diameter: 1mm 
 * Conductor: 26 AWG;  20/0.08, Tinned CU
 * Wire ending: JST-GH
 
## Color scheme
For easy orientation in avionics cabling cables have a common ThunderFly color scheme. Each type of signal/cable has own color combination. 


## I2C

|Signal | Pixhawk Color | ThunderFly color | 
|--------|------------------|---------------------|
| +5V  | Red             |   ![red](https://user-images.githubusercontent.com/5196729/102204855-ab1c3300-3eca-11eb-8083-646d633e3aef.png) Red                   |
| SCL  | Black          |  ![yellow](https://user-images.githubusercontent.com/5196729/102204908-bc653f80-3eca-11eb-9a1d-a02ea5481c03.png) Yellow                | 
| SDA  | Black          |  ![green](https://user-images.githubusercontent.com/5196729/102205114-04846200-3ecb-11eb-8eb8-251c7e564707.png) Green                |
| GND | Black          | ![black](https://user-images.githubusercontent.com/5196729/102204896-b8d1b880-3eca-11eb-8b73-656cac9104e4.png) Black                 |


#### Cable turning 
- 10 turns for each pair  SCL/+5V and SDA/GND per 30cm cable length
- 4 turns of both pairs together per 30cm cable length. 


## UAVCAN

|Signal | Pixhawk Color | ThunderFly color |
|--------|------------------|---------------------|
| +5V  |        Red       | ![red](https://user-images.githubusercontent.com/5196729/102204855-ab1c3300-3eca-11eb-8083-646d633e3aef.png) Red                 | 
| CAN_H  |  Black     | ![white](https://user-images.githubusercontent.com/5196729/102204632-5e385c80-3eca-11eb-985d-a881acfae26a.png) White              |
| CAN_L |    Black     | ![yellow](https://user-images.githubusercontent.com/5196729/102204908-bc653f80-3eca-11eb-9a1d-a02ea5481c03.png) Yellow             |
| GND |        Black    | ![black](https://user-images.githubusercontent.com/5196729/102204896-b8d1b880-3eca-11eb-8b73-656cac9104e4.png) Black               | 


#### Cable turning 
- 10 turns for each pair GND/+5V and CAN_L/CAN_H per 30cm cable length
- 4 turns of both pairs together per 30cm cable length. 

