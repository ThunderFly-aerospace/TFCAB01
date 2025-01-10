The [TFCABxxCAN01](https://github.com/ThunderFly-aerospace/TFCAB01) cable is the ideal solution for data transmission on the CAN bus in drones with avionics that conform to the [Pixhawk standard](https://github.com/pixhawk/Pixhawk-Standards/blob/master/DS-009%20Pixhawk%20Connector%20Standard.pdf). The cable is manufactured to high performance and reliable connection and a twisted design that reduces internal cross-talk and minimizes its own capacitance, ensuring a reliable and efficient transmission.

The cable utilizes the original JST-GH plastic connectors, ensuring a secure and seamless connection between your drone's components. The used color scheme that corresponds to the [ThunderFly](https://www.thunderfly.cz/) color standard described in the [PX4 documentation](https://docs.px4.io/main/en/assembly/cable_wiring.html#i2c-cables), you can easily identify the type of bus to expect in the cable, reducing the possibility of incorrect connection.

The wires are made of high-quality tinned copper wires with silicone insulation, ensuring high flexibility and mechanical durability of the resulting cable. The silicone wire is a 26AWG with an outer diameter of 1.0 mm and short-term high-temperature resistance up to 200 °C.

### Parameters

 - Lengths: 15, 30, and 45 cm (Choose the desired length after inserting it into the cart)
 - Connector type: JST-GH
 - Number of pins: 4
 - Designed for: [I2C bus](https://en.wikipedia.org/wiki/I%C2%B2C)

### Pinout

| Pin number | Color | Signal |
| -------- | -------- | -------- |
| 1 | Red | VCC (5.4V) |
| 2 | White | CAN H |
| 3 | Yellow | CAN L |
| 4 | Black | GND |

#### Warning:
Despite having the same type of connector and number of conductors, this cable is not recommended for use on the I2C bus. The I2C bus requires a different cable twisting that provides good resistance to EMI interference. The [TFCABxxI2C01](https://www.tindie.com/products/30113/) cable is suitable for the I2C bus.
