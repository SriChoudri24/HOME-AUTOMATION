# HOME-AUTOMATION

*COMPANY NAME*:CODTECH IT SOLUTION

*NAME*: R.SRI CHOUDRI

*INTERN ID*:CT04DH963

*DOMAIN*:INTERNET OF THINGS

*DURATION*:4 WEEKS

*MENTOR*:NEELA SANTHOSH


# 🏠 Task 2: Home Automation System – IoT Internship (CODTECH IT Solutions)

## 📘 Overview

As part of my IoT internship at *CODTECH IT Solutions, I developed a simple **Home Automation System* using Arduino UNO and the Wokwi online simulator. This project simulates the control of home appliances — specifically a *Blue LED as a Light* and a *Red LED as a Fan* — using the *Serial Monitor* as a virtual app interface.

## ⚙ Functionality

- A → Turns ON the *Light (Blue LED)*
- a → Turns OFF the Light
- B → Turns ON the *Fan (Red LED)*
- b → Turns OFF the Fan

Commands are sent via the Serial Monitor to simulate mobile app control.

## 🛠 Tools & Components

- Arduino UNO (Wokwi)
- Blue LED (Light)
- Red LED (Fan)
- 2 x 220Ω Resistors
- Jumper Wires
- Serial Monitor (App simulation)

## 🔌 Circuit Setup

| Device | Arduino Pin | LED Color | Resistor | GND |
|--------|-------------|-----------|----------|-----|
| Light  | 13          | Blue      | 220Ω     | ✅  |
| Fan    | 12          | Red       | 220Ω     | ✅  |

- Each LED's anode is connected to the respective digital pin.
- Each cathode is connected to GND via a 220Ω resistor.

## 💻 Code Summary

The Arduino reads characters from the Serial Monitor and toggles each output pin accordingly to control the simulated appliances.

## ✅ Status

✅ Successfully tested on Wokwi Simulator  
💡 Blue LED = Light, 🔴 Red LED = Fan

## 🔗 Simulation Link https://wokwi.com/projects/438355079527289857

[Click here to open in Wokwi](#) (Insert your Wokwi link here)

OUTPUT

<img width="960" height="540" alt="Image" src="https://github.com/user-attachments/assets/06925950-7074-4bc2-99f3-d3c624569d4d" />
---
