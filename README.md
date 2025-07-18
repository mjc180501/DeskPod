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
# Bill of Materials

| Component              | Description                           | Link                                                                                                                                                                                                                                               | Cost  |
|------------------------|----------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------|
| **OLED 128x64**        | Small display for state text           | [AliExpress](https://www.aliexpress.us/item/3256805954920554.html)                                                                                                                                                                                | $0.99 |
| **Arduino Nano**       | Microcontroller for logic and control  | [AliExpress](https://www.aliexpress.us/item/3256809081358829.html)                                                                                                                                                                                | $0.99 |
| **3×AAA Battery Case** | Holds 3 AAA batteries to power servo   | [AliExpress](https://www.aliexpress.us/item/3256806038995262.html)                                                                                                                                                                                | $2.75 |
| **9V Battery**         | Powers the Arduino Nano                | [Alibaba](https://www.alibaba.com/product-detail/GMCELL-Heavy-Duty-Battery-Carbon-Zinc_1600319349029.html)                                                                                                                                        | $0.22 |
| **10kΩ Resistor**      | Resistor for the OLED display          | I already have this                                                                                                                                                                                                                               | N/A   |
| **10µF Capacitor**     | Ceramic capacitor for OLED             | [AliExpress](https://www.aliexpress.us/item/3256802104127109.html)                                                                                                                                                                                | $1.50 |
| **Case Top**           | Rotating part of the timer             | I have access to a 3D printer                                                                                                                                                                                                                     | N/A   |
| **Case Bottom**        | Bottom part of the enclosure           | I have access to a 3D printer                                                                                                                                                                                                                     | N/A   |
| **Case Body**          | Main middle structure of the case      | I have access to a 3D printer                                                                                                                                                                                                                     | N/A   |
| **3 Push Buttons**     | Input for user interaction             | [AliExpress](https://www.aliexpress.us/item/2251832629654875.html)                                                                                                                                                                                | $1.56 |
| **Servo (SG90)**       | Indicates state progress               | [AliExpress](https://www.aliexpress.us/item/3256807057292912.html)                                                                                                                                                                                | $2.10 |






