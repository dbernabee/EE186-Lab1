# ⭐EE186-Lab1⭐

## Flashing & Debugging Deliverables (Part 2)
##### During the flashing process 2 LEDS turn on. LD6 flashes green, LD4 flashes green and red. A .elf file is generated. The IDE uses ST-LINK to program the MCU's FLASH memory, which is then reset to run new code. The general-purpose registers (volatile memory) is written to on the MCU. The ST-LINK debugger allows the STM32CubeIDE to communicate with the board, which requires a USB cable connection. The ST-LINK debugger transfers the data to the MCU using the Serial Wire Debug interface.

<img width="914" height="543" alt="image" src="https://github.com/user-attachments/assets/fcaec006-70bc-439f-8528-351ee445433c" />
<img width="914" height="543" alt="image" src="https://github.com/user-attachments/assets/82ab3445-39e8-4232-bbf9-9d2f2840e7c7" />

## Blinking LEDs Deliverables (Part 3)
##### On the NUCLEO-L4R5ZI-P board there 3 user LEDS available, which are LD1, LD2, and LD3. LD1 is a green user LED that is connected to the STM32 I/O PC7. LD2 is a blue user LED that is connected to PB7. LD3 is a red user LED that is connected to PB14. These user LEDs are on when the I/O is HIGH value, and are off when the I/O is LOW. These pins are configured as GPIOs which means that each LED is configured within their respective GPIO port. They should be configured as output because the board needs to make the LEDs either HIGH or LOW, which requires the pins to be an output. 

<img width="1752" height="1032" alt="image" src="https://github.com/user-attachments/assets/59b27ccc-1a29-46e8-8e6e-afc4b924f4ae" />






