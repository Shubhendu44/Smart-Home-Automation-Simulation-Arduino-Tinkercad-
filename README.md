# Smart-Home-Automation-Simulation-With-Arduino-using-Tinkercad

Mini Home Automation Dashboard (Arduino + Tinkercad)

A simulated home automation system built using Arduino (Embedded C++) and Tinkercad, featuring:

- Password-protected access  
- Real-time appliance control  
- Device status monitoring  
- Non-blocking scheduling (using millis())  

**This project requires no physical hardware and runs entirely in Tinkercad.**

---

##  Features

### Password Login  
Commands are locked until the user logs in:
LOGIN 1234

### Control Appliances (A, B, C, D)
Example:
ON A

### Status Command  
Shows ON/OFF status of all devices:
STATUS

### Scheduling System  
Schedule future ON/OFF actions:
SCHEDULE C ON AFTER 2
SCHEDULE D ON AFTER 4

- Supports up to **4 scheduled tasks** (one for each device)  
- Uses **millis()** → non-blocking real-time scheduling  

---

## Circuit (Tinkercad)

| Device | Arduino Pin | Component             |
|--------|-------------|------------------------|
| A      | 2           | LED + 220Ω (RED)       |
| B      | 3           | LED + 220Ω (GREEN)     |
| C      | 4           | LED + 220Ω (YELLOW)    |
| D      | 5           | LED + 220Ω (BLUE)      |

All LED cathodes → **GND**  
No additional components required.

---

## Run Instructions

1. Open the project in Tinkercad  
2. Upload the `.ino` code  
3. Start the simulation  
4. Open Serial Monitor  
   - **Baud:** 9600  
   - **Line ending:** Newline  
5. Login using: 
LOGIN 1234

6. Start controlling devices or scheduling tasks.

---

## Technologies Used

- Embedded C++ (Arduino)  
- Microcontroller programming (ATmega328P)  
- UART serial communication  
- Finite State Machine (login state)  
- Real-time scheduling using millis()  
- Event-driven programming  

---

## Demo Pic
<img width="1919" height="830" alt="Screenshot 2025-11-16 163648" src="https://github.com/user-attachments/assets/dbaf33d1-997c-4653-9b14-038ed8258653" />

---

## Project Link

🔗 **Tinkercad Project:**  
https://www.tinkercad.com/things/hP73FjaHDJw-smart-home-automation-using-arduino?sharecode=7zarvoWvZw-IVgAKhE8fRN9Z-cI7aPLlbfVlLRdFm2s





