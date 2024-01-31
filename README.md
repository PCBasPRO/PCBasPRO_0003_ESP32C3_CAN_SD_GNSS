# PCBasPRO_0003_ESP32C3_CAN_SD_GNSS
PCB to Study the feasibility of ESP32 on [0002](https://github.com/PCBasPRO/PCBasPRO_0002_Cheap_FOC2VESC)

## **NOTE: Ongoing updates on text description, PCB and Schematic**


### **Features:**

- 5V input (via CAN or USB)
- Digital power auto-select CAN, or USB or Battery ( in this order)
- Battery charger ready (100mA-500mA configurable, Led and battery manager unpopulated )
- GNSS connector (ongoing pin selection), or GNSS on Board L80 or L80R or L86 (electrolitic capacitor as a bulk and diode unpopulated)
- CAN Input
- Usb input
- SD input
- Esp32C3 with internal PCB antena
- ESD ready (not populated)
- 3v3 LDO
- 19.6x50mm (easybreak for 43.3mm, 46.3mm, 47mm ) PCB  (First draft- 31mmX38mm PCB)
   ufl conection ready (not for L80R, unpopulated)
- VESC pin compatible
    - CAN_TX			  1
    - CAN_RX			  0
    - MOSI				  4
    - MISO				  6
    - SCK				  	5
    - CS					  7
    - UART_TX				21
    - UART_RX				20
    - LED_RED_PIN		2
    - LED_BLUE_PIN	3

### **Current limitations:**

  - 3V3 LDO 500mA

### **My next steps:**

- See if a display can be integrated  (GPIO10 pin on UART connector)


### **PCB Status:**
TOP:
![Image](https://github.com/PCBasPRO/PCBasPRO_0003_ESP32C3_CAN_SD_GNSS/blob/main/2024-01-30_21h04_01.png)
![Image]()
Bottom:
![Image]()

First draft TOP: 
![Image](https://github.com/PCBasPRO/PCBasPRO_0003_ESP32C3_CAN_SD_GNSS/blob/main/2024-01-14_11h23_50.png)
First draft Bottom:
![Image](https://github.com/PCBasPRO/PCBasPRO_0003_ESP32C3_CAN_SD_GNSS/blob/main/2024-01-14_11h25_02.png)
