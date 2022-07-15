# energy-monitoring

## Components

### Gas
- Itron Cyble Sensor v2 (K1), 2-pole
- Homematic HM-ES-TX-WM
- Homematic CCU3

#### Installation
- Connect 2, 4, and 5 to one sensor pole
- Insert a 110 kOhm resistor between 3 and 6, connect 6 to the other sensor pole
- Connect sensor to HM-ES-TX-WM *before* inserting batteries into HM-ES-TX-WM
- Teach-in the HM-ES-TX-WM at the CCU3, a gas sensor will be automatically detected
