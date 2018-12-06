# JohnFlorek
When single phase motors startup, the motor shaft needs a lot of initial power to start running.
This amount of inrush current is too much for power lines to safely provide, and can lead to regional brownouts. 
Our single-phase motor startup system will switch the motor from the electric grid to a power supply during startup. 
Once the motor shaft speed has normalized, we will reconnect the motor to the grid. 
If, for some reason, the motor fails to start even when drawing power from the battery, it will be disconnected from all power 
sources to prevent motor damage.
We will be using a full H-bridge inverter circuit design, printed on a PCB, 
to convert the battery DC voltage to AC voltage for the motor to consume. 
We will be controlling the transistors in this circuit, as well as a solid state relay, using a microcontroller.
Our code, schematics, and simulations will be uploaded for this project. We will update this page periodically as our design progresses.
