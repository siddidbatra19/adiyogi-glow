# adiyogi-glow
A custom printed circuit board designed to act as an animated backlight for a 3D-printed statue of Lord Shiva. The circuit uses a 555 timer to generate a clock pulse and a CD4017 decade counter to create a chasing LED sequence.
<img width="1594" height="1192" alt="image" src="https://github.com/user-attachments/assets/e01bdeef-4474-418d-85b2-e92e9861f0ec" />
<img width="1785" height="1178" alt="image" src="https://github.com/user-attachments/assets/6cddb8f2-cf89-4a1d-baa6-a34da6316bca" />


# Overview & Design Process
This project was designed in KiCad over the course of about 4 hours.

# Hardware & 3D Integration
I built this specific PCB layout to serve as a custom lighting fixture for a 100mm x 100mm 3D-printed statue. The PCB dimensions were strictly constrained to remain completely hidden behind the print. 

To achieve a glowing halo effect:
* The 5mm LED footprints are routed in an inverted "U" shape along the perimeter of the board.
* The LEDs will be reverse-mounted on the back of the PCB. 
* When powered, the chasing sequence will smoothly frame the statue from behind.

# Bill of Materials (BOM)
https://docs.google.com/spreadsheets/d/1dknvj6RsMCPzlCs72U_A4Biw2XVm9xkfnfsrWRNoysQ/edit?usp=sharing

## Manufacturing
To manufacture this board, download `gerber.zip` from the root directory and upload it to a fab house like JLCPCB. The board is designed with standard 2-layer specifications and fits within a 100x100mm footprint.
