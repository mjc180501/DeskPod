# DeskPod
Podomoro Timer Desk Assistant

This project is a Podomoro timer with a spinning servo like a kitchen timer that moves in according to Podomoro phase and time. There is an OLED screen to show the focus stage and buttons to start, reset, and stop. 

I made this because I love using the Podomoro timer website and I think it would be super cool to have my own physical example of it. It would also be a cool thing to have on my desk while studying, and I want to learn how to control a servo. 

Schematic:

<img width="603" alt="Screenshot 2025-06-28 at 9 49 00 PM" src="https://github.com/user-attachments/assets/e9cb6bea-1aa8-4037-a737-3815d77975a1" />


Rendered Pictures:

<img width="486" alt="Screenshot 2025-06-28 at 12 56 31 PM" src="https://github.com/user-attachments/assets/a56b7580-7c13-4597-a2de-bbd89e97cdb1" />
<img width="536" alt="Screenshot 2025-06-28 at 12 56 05 PM" src="https://github.com/user-attachments/assets/f9406792-48c9-43b1-8ef2-89cf3ba177ec" />
<img width="594" alt="Screenshot 2025-06-28 at 12 55 36 PM" src="https://github.com/user-attachments/assets/c3041884-25dc-465d-91b6-8e077919ca7c" />



BOM:
| Component              | Description                           | Link                                                                                                                  | Cost   |
| ---------------------- | ------------------------------------- | --------------------------------------------------------------------------------------------------------------------- | ------ |
| **OLED 128x64**        | Small display for state text          | [AliExpress](https://www.aliexpress.us/item/3256805913100103.html)                                                    | \$2.38 |
| **Arduino Nano**       | Microcontroller for logic and control | [Alibaba](https://www.alibaba.com/pla/good-quality-Arduino-Nano-V30-CH340G_1600942840347.html)                        | \$2.20 |
| **3×AAA Battery Case** | Holds 3 AAA batteries to power servo  | [DigiKey](https://www.digikey.com/en/products/detail/keystone-electronics/2484CN/7385289)                             | \$2.45 |
| **9V Battery**         | Powers the Arduino Nano               | [DigiKey](https://www.digikey.com/en/products/detail/duracell-industrial-operations-inc/9V/21259959)                  | \$4.46 |
| **10kΩ Resistor**      | Resistor for the OLED display         | Already have                                                                                                          | N/A    |
| **10µF Capacitor**     | Ceramic capacitor for OLED            | [Mouser](https://www.mouser.com/ProductDetail/Vishay-BC-Components/D471K25X5FL63L6R?qs=WcHCFKihsBqnFBaLsk7srQ%3D%3D)  | \$0.58 |
| **Case Top**           | Rotating part of the timer            | Ship through Hack Club                                                                                                | N/A    |
| **Case Bottom**        | Bottom part of the enclosure          | Ship through Hack Club                                                                                                | N/A    |
| **Case Body**          | Main middle structure of the case     | Ship through Hack Club                                                                                                | N/A    |
| **3 Push Buttons**     | Input for user interaction            | [DigiKey](https://www.digikey.com/en/products/detail/same-sky-formerly-cui-devices-/TS02-66-60-BK-160-LCR-D/15634268) | \$0.30 |
| **Servo (SG90)**       | Indicates state progress              | [Alibaba](https://www.alibaba.com/product-detail/Stock-9G-Micro-Servo-Motor-SG90_1601038670928.html)                  | \$0.57 |





