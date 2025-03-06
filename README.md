# 🛰️ Zenith Altimeter

### **Creating competitive altimeters, packed with features, at an affordable price**  

---

# 📌 Features  
✅ High G 3-axis Accelerometer <br>
✅ Adjustable Launch detection<br>
✅ Apogee Detection<br>
✅ Micro SD card slot with latch mechanism<br>
✅ Will be compatible with Cosmic Tower in the future<br>
✅ High resolution recording<br>
✅ Small package size  <br>
✅ Light weight <br>

# 🦺 Safety Features

## ARMING terminal
Pyrotechnics may only be enabled if and only if this terminal is shorted during launch day. It is crucial that this terminal
is not shorted during the debugging stage of the rocket.

## BYPASS terminal
The Pypass terminal will ensure that the rockets main power source is not souly relying on the physical toggle switch. You MUST
properly short this terminal during launch, not doing so WILL cause your rocket to malfunction and have a catastrophic failure.

## CONTINUITY indicator
Underneath the pyrotechnic terminal is an LED which will shine a very bright GREEN light when the terminal has continuity. This visual
queue will let the user know that the pyro channel is LIVE and ready to go. Note that the LED can only show continuity if and only if
the ARM terminal is also shorted.

## ACCELEROMETER & BAROMETER Based Apogee Detection
The Zenith Altimeter comes with a dual deployement system which check data from both sensors on board the altimeter. Combining the accelerometer 
and barometric pressure sensor's data, we can accuratly detect apogee without false triggers.

## LAUNCH DETECTION
The rocket only enters flight mode if and only if the launch detection parameter is less than the current vertical acceleration of the rocket. The sensitivity (value) of the launch detection can be modified in the Cosmic Tower (future compatibility).

## PARACHUTE DELAY
Using the Cosmic Tower (future availability), the user may change various paramters, this includes an apogee delay in the case the rocket enters high altitudes where the user may want the rocket to freefall. An apogee delay is also useful to ensure the rocket is indeed past apogee and has a lowest speed in order not to damage the shoot or apply stress onto the rocket.

---

## 📋 Specifications  

| Feature           | Details                                  |
|------------------|----------------------------------|
| **Processor**    | STM32F411CEU6               |
| **Sensors Models**      | MS5607 & ADXL375  |
| **Storage**      | Micro-SD card      |
| **Power**        | INPUT: 3.7 - 13.5 V to 3.3V OUT       |
| **Deployment**   | 1 Pyro-Channel        |
| **Telemetry**    | Not available on Zenith       |
| **Interfaces**   | USB/Serial (DFU protocol)              |
| **Firmware**     | Programmed in C/C++, .bin for firmware updates  |
| **Altitude Range** | 0 - 100 000ft , 0 - 30km |
| **Acceleration recording**| ± 200G |
| **MAX G Shock | 10 000G Shock survival (ADXL Only) |

---

## 📏 Dimensions & Weight  

| Parameter       | Value               |
|----------------|---------------------|
| **Size (Fully Assembled)**       | 55.00 x 25.00 x 12 mm |
| **Weight**     | 10 grams            |

---
*"Note that this Repository is new and is still under development. Please be patient as more information is soon to come!" - Cosmic Aerospace Technologies*
