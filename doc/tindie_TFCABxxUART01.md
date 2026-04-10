The [TFCABxxUART01](https://github.com/ThunderFly-aerospace/TFCAB01) cable is used for data transmission on the Serial links in drones with avionics that conform to the [Pixhawk standard](https://github.com/pixhawk/Pixhawk-Standards/blob/master/DS-009%20Pixhawk%20Connector%20Standard.pdf). The cable is manufactured to high performance and reliable connection.

The cable utilizes the original JST-GH plastic connectors, ensuring a secure connection between your drone's components. The used color scheme that corresponds to the [ThunderFly](https://www.thunderfly.cz/) color standard described in the [ThunderFly documentation](https://docs.thunderfly.cz/avionics/TFCAB01/#uarttelemserial-cables), you can easily identify the type of bus to expect in the cable, reducing the possibility of incorrect connection.

The wires are made of high-quality tinned copper wires with silicone insulation, ensuring high flexibility and mechanical durability of the resulting cable. The silicone wire is a 26AWG with an outer diameter of 1.0 mm and short-term high-temperature resistance up to 200 °C.

### Parameters

 - Lengths: 15, 30, and 45 cm (Choose the desired length after inserting it into the cart)
 - Connector type: JST-GH
 - Number of pins: 6
 - Designed for: [I2C bus](https://en.wikipedia.org/wiki/I%C2%B2C)

### Pinout

| Pin Number | Color | Signal |
|------------|-----------------|--------|
| 1          | ![red](https://user-images.githubusercontent.com/5196729/102204855-ab1c3300-3eca-11eb-8083-646d633e3aef.png) Red | VCC (5.4V) |
| 2          | ![white](https://user-images.githubusercontent.com/5196729/102204632-5e385c80-3eca-11eb-985d-a881acfae26a.png) White | TX |
| 3          | ![green](https://user-images.githubusercontent.com/5196729/102205114-04846200-3ecb-11eb-8eb8-251c7e564707.png) Green | RX |
| 4          | ![blue](https://user-images.githubusercontent.com/5196729/102205102-ffbfae00-3eca-11eb-9372-8406f7a4aa9d.png) Blue | CTS |
| 5          | ![yellow](https://user-images.githubusercontent.com/5196729/102204908-bc653f80-3eca-11eb-9a1d-a02ea5481c03.png) Yellow | RTS |
| 6          | ![black](https://user-images.githubusercontent.com/5196729/102205213-28e03e80-3ecb-11eb-95bb-7ba207360541.png) Black | GND |

### Important Notes
- **UART cables should be kept as short as possible** to minimize EMI interference.
- **Twisting is not recommended** for UART cables to prevent increased cross-talk.
- **Straight-through wiring**: Ensure that RX/TX and RTS/CTS are properly swapped in device connectors. The cable itself is 1:1.

