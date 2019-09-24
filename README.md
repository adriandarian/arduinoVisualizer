# Arduino Visualizer

[![Greenkeeper badge](https://badges.greenkeeper.io/adriandarian/arduinoVisualizer.svg)](https://greenkeeper.io/)

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
    - `yarn install` or `npm install`
    - Open two terminals
        - First terminal
            > `yarn start` or `npm run start`
        - Second terminal
            > `yarn server` or `npm run server`
    - Visit **http://localhost:3000**

## License

MIT license. Copyright © 2019.
