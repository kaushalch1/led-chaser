# Compass LED Chaser – Travel Edition

## Overview

The **Compass LED Chaser – Travel Edition** is a travel-inspired PCB project that combines creativity with fundamental digital electronics. Designed in the shape of a compass, the board features eight LEDs arranged around the compass points. The LEDs illuminate sequentially, creating the appearance of a rotating navigation beacon, symbolizing exploration, adventure, and the excitement of discovering new destinations.

Powered via **USB Type-C**, the project is portable and can be used with a power bank, laptop, or USB charger, making it an ideal travel companion or desk decoration.

---

## Inspiration

A compass has guided travelers, explorers, sailors, and adventurers for centuries. This project celebrates the spirit of travel by transforming a simple LED chaser into an interactive compass that reminds users to keep exploring new places.

Rather than simply blinking LEDs, the board represents movement, direction, and the journey toward the next adventure.

---

## Features

- Compass-shaped PCB
- Eight LEDs arranged around the compass
- Sequential LED chasing effect
- Adjustable animation speed
- USB Type-C powered
- ON/OFF power switch
- Reset button to restart the sequence
- Compact and portable design
- Beginner-friendly digital electronics project

---

## Components Used

| Component | Quantity |
|-----------|---------:|
| NE555 Timer IC | 1 |
| CD4017 Decade Counter | 1 |
| LEDs | 8 |
| 330 Ω Resistors | 8 |
| 1 kΩ Resistor | 1 |
| 10 kΩ Resistor | 1 |
| 50 kΩ Potentiometer | 1 |
| 1 µF Capacitor | 1 |
| 0.01 µF Capacitor | 1 |
| 100 nF Capacitors | 2 |
| 10 µF Capacitor | 1 |
| USB Type-C Connector | 1 |
| Slide ON/OFF Switch | 1 |
| Push Button (Reset) | 1 |

---

## How It Works

The project uses an **NE555 Timer** configured in astable mode to generate continuous clock pulses.

These clock pulses are sent to the **CD4017 Decade Counter**, which activates one output at a time. Each output drives one LED positioned around the compass.

After the eighth LED lights, the counter resets and the sequence begins again, creating a smooth rotating light effect similar to a spinning compass indicator.

The potentiometer allows the user to control the speed of the animation, while the reset button restarts the sequence from the North direction.

---

## Travel Applications

Although designed primarily as an educational electronics project, the Compass LED Chaser has several travel-themed uses:

- Decorative travel desk accessory
- Portable campsite or hostel mood light
- Travel souvenir showcasing PCB art
- Educational demonstration of navigation-inspired electronics
- Conversation starter for makers and travelers
- Gift for travel and adventure enthusiasts

---

## Learning Outcomes

This project demonstrates:

- PCB design using KiCad
- USB Type-C power integration
- 555 timer operation
- CD4017 decade counter operation
- Sequential LED control
- Electronic schematic design
- PCB routing techniques
- Through-hole component assembly

---

## Future Improvements

Possible future enhancements include:

- Rechargeable Li-ion battery support
- Battery charging circuit
- Automatic brightness control
- Ambient light sensor
- RGB LEDs
- Sound effects
- Magnetic compass module
- Microcontroller-based animation modes
- Touch controls
- Power bank functionality

---The Compass LED Chaser represents the excitement of exploration and the joy of travel. Each rotating LED symbolizes taking the next step toward discovering new places, cultures, and experiences. It serves as a reminder that every adventure starts by choosing a direction and moving forward.

schematic files
<img width="1917" height="1015" alt="image" src="https://github.com/user-attachments/assets/44df2f70-35b8-4f1e-872b-0c56458a7b17" />
pcb files
<img width="1917" height="1016" alt="image" src="https://github.com/user-attachments/assets/3de7bcb4-49c5-4c6c-a4b7-5893b843acaf" />


## License

This project is open-source and may be used, modified, and shared for educational and personal purposes.
