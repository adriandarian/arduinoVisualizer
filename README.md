# Arduino Visualizer

> This is a simple Node.js application to monitor realtime temperature from Arduino Uno R3. This project also contains the Morris charting library.

## Hardware Requirements

- Arduino Uno R3 board
- 1k ohms resistor
- 1k Thermistor
- 3 jumper wires (M to M)
- Breadboard
- Desktop

## Software Requirements

- Arduino IDE
- Node.js

## Pre-requisites

- Upload the code of standard firmata to Arduino
- Connect the ground, 5v jumper wires accordingly
- Connect the data jumper wire to Analog pin-0

## Get started

    - git clone https://github.com/adriandarian/arduinoVisualizer.git
    - Navigate to the folder  
      > `cd server/`
    - `yarn install`
    - Open two terminals
        - First terminal
            > `yarn start`
        - Second terminal
            > `yarn server`
    - Visit **http://localhost:3000**

## License

MIT license. Copyright © 2019.