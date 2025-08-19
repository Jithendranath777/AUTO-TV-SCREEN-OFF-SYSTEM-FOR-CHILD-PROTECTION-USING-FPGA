Project Overview:
This project is designed to enhance child safety by automatically turning off the TV screen when a child gets too close to it. The system uses an ultrasonic sensor to detect the distance between the child and the screen. If the distance falls below a safe limit, the FPGA processes the data and turns off the display immediately. Once the child moves away to a safe distance, the display is turned back on. This smart solution helps reduce eye strain and protects children's vision by ensuring they watch TV from a healthy distance.

Key Features:

Successfully designed and implemented an FPGA-based system to monitor child presence and automatically control TV screen status.

Ensures child eye protection by limiting prolonged exposure to TV screens.

Utilized Verilog HDL for modular, hardware-level design—efficient, reliable, and real-time.

Integrated Ultrasonic Sensor and VGA Control for seamless detection and response.

Power-efficient and independent of smart TV functionalities, making it ideal for all screen types.

Scalable solution that can be extended with AI-based detection or mobile alerts in the future.

Promotes responsible technology use for healthier child development.

Components Used:

Ultrasonic Sensor (HC-SR04)

Jumper Wires

USB Cable

VGA Cable

VGA Monitor

FPGA EDGE Artix-7 Board

Xilinx Vivado Software

Working Principle:

The ultrasonic sensor measures the distance between the child and the TV screen.

If the child comes closer than the pre-defined safe distance, the FPGA processes the signal.

The FPGA then controls the VGA output and turns off the display.

When the child moves back to a safe distance, the FPGA automatically restores the display.

Applications:

Home entertainment systems for safe TV viewing.

Educational environments where children use large displays.

Public information displays for crowd safety management.

Future Scope:

AI-based detection for enhanced accuracy.

Mobile alerts for parental monitoring.

Extension to other display systems beyond TVs.

Conclusion:
This project demonstrates how FPGA technology, when integrated with simple sensors, can provide innovative and practical solutions for child protection. It ensures safe and responsible TV usage, promoting healthier vision and better child development.
