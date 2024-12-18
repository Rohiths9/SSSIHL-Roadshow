Workshop Overview
Attended a one-day workshop introducing VLSI and RISC-V by Mr Kunal Gosh and team.
Learned about the chip design process, microprocessors, and  in VLSI.
Setup Process

Commands Used:

Installed gedit via sudo apt install gedit.
Used GCC and RISC-V toolchains for compiling and testing code.
Chip Design Process with OpenLane

Synthesis:

Command: run_synthesis
Converts high-level code to gate-level design.

Floorplanning:

Command: run_floorplan
Defines layout structure of the chip.
Placement:

Command: run_placement
Places logical components physically on the chip.
Clock Tree Synthesis (CTS):

Command: run_cts
Distributes clock signal across the chip.
Routing:

Command: run_routing
Connects all cells with metal layers to form interconnections.
Programming Boards with RISC-V

Blinking LED Example:

Code made the LED blink faster by tweaking the Delay_Ms() function.
LED Fade Effect:

PWM-based code created a fading effect by modifying duty cycles.
Observations
You successfully created and tested chip layouts, ran RISC-V code, and observed real-time effects on physical boards.
Acknowledgments
Thanked Mr. Kunal Ghosh, his team, the institute, and the department for this amazing learning opportunity.
