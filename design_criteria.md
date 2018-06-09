# Design criteria Open Field Mill

## Features
* Electrostatic field strength measurement [0-1MV/m]
* SD card data logging

## Sensor
Circular sensor cut in a trefoil shape. Outer diameter 3,5", inner diameter 1", cutouts 60°
Sensor 6mm above a ground plane.
Sensor commutated by a 3,5" inch trefoil mounted 3mm above the sensor plate.
Sensor area is 28,5cm^2, at an height of 6mm i covers a volume of 17,1cm^3

## Field enery dissiation
The assumption is that the field energy has to be dissipated through the input amplifier of the circuit. The signal frequency is 300Hz so the discharge time is 1/600sec and the charge time is 1/600sec.

## Electrostatic potential energy in different fields
ε_0 = 8,854187817e-12
ω=1/2 * ε_0 * E^2

| Field strength (E)| Field energy density (ω)| Energy in 17,1cm^2 | Average current |
|-------------------|-------------------------|--------------------|-----------------|
| 1V/m              | 4,42709E-12 J/m^3       | 7,57094E-17 J      | 4,54256E-14     |
| 1kV/m             | 4,42709E-06 J/m^3       | 7,57094E-11 J      | 4,54256E-08     |
| 1MV/m             | 4,427093909 J/m^3       | 7,57094E-05 J      | 0,045425642     |

## Electrostatic potential energy in a volume equal to that covered by the sensor.

### 1V/m
E = 1V/m
ω=4,42709E-12 J/m^3

### 1kV/m
E = 1kV/m

ω=4,42709E-06 J/m^3

### 1MV/m
E = 1MV/m
ω=4,427093909 J/m^3
