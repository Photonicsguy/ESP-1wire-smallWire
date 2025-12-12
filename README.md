# ESP-1wire-smallWire
Small ESPHome module using an ESP-01M for 1wire sensors
- 1Wire bus protected by a polyfuse, with simply bus fault detection (1Wire bus power connected to GPIO3 after polyfuse)
- 1Wire bus IO is on GPIO03
- Mostly 0802 size SMD components

## Components
- ESP-01M
- DS18B20 1Wire temperature sensor
- 4x2 pin header (optional socket for ESP-01M)
   - Digikey: 732-61300821821-ND
- 100mA polyfuse
 - Digikey: 13-BK60-010-DZ-ND
- 3.3V Reg, HT7333-A, SOT89
 - Digikey: 4518-HT7333-ACT-ND
- 2x10K Resistor, 0802
- 4.7K Resistor, 0802
- 62 Ohm Resistor, 0802
- 10uF Capacitor, 4x4.5
- 479pF Capacitor, 0802
- JST Connectors or other connector of your choice
 - 2 pin for power
 - 3 pin for 1Wire
