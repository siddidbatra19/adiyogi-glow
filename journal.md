**LED chaser**
I spent around 4–5 hours designing and routing the PCB in KiCad. I used Hack Club’s **Blinky starter project** as a starting point to understand the basic circuit and get some guidance on how to set up the board. From there, I designed the actual PCB layout myself and made the changes needed to fit the project.

The main goal of the PCB is to work as a backlight for a 3D-printed statue of Lord Shiva that I made. Before starting the PCB design, I measured the statue and found that it was roughly **100 mm × 78 mm**. Since the PCB is going to sit directly behind the print, I wanted to make sure it would not stick out from behind the statue or be visible from the front. Because of this, the overall PCB dimensions were constrained to fit within the size of the print.

<img width="2749" height="2174" alt="IMG_2250" src="https://github.com/user-attachments/assets/eaf9ed05-ed07-4830-92fd-f9b12898eb5d" />

For the LED placement, I decided to use a **reverse “U” pattern** around the perimeter of the board. The idea was to spread the LEDs around the outside rather than concentrating them in one area. This should help create a more even glow around the statue and make the lighting effect more noticeable.

The LEDs will be mounted on the **back side of the PCB**, facing toward the 3D print. This keeps the components hidden and allows the light to shine through/around the edges of the print instead of having the LEDs visible from the front.

<img width="1628" height="1253" alt="Screenshot 2026-08-23 001750" src="https://github.com/user-attachments/assets/e36844ec-32b4-482a-9019-0cf67dd4ccfb" />

After placing the components, I routed the traces manually in KiCad. I spent a good amount of time figuring out how to route everything while keeping the board compact and making sure the traces didn't interfere with the other components. Since the board needed to stay within the dimensions of the statue, I couldn't simply make the PCB larger to make routing easier.

The final result is a custom PCB designed specifically for this 3D print. When the circuit is powered, the LEDs will chase around the perimeter of the board, creating a moving glow behind the statue. The lighting effect is meant to add another layer to the 3D print rather than just acting as a basic light source.

<img width="1785" height="1178" alt="pcb_back" src="https://github.com/user-attachments/assets/b6624889-cc7d-44ea-a896-192329093463" />
