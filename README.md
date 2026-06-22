Simple inverse pendulum using 3d printed parts and cheap electronics.
Electronics used:
ESP 32 devkit
SimpleFOC mini
AS5600 Magnetic Encoder
Brusheles DC motor MiToot 2206/100T

Results:
(insert video from 2026-06-22)

Issues:
The motor is too weak for the current construction and heavy bearings.
The magnetic encoders have a very noisy output of velocity because they measure position.
The code is poorly optimised and one cycle takes up to 1ms
