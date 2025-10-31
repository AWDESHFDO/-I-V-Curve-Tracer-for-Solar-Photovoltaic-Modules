This project presents the design and development of a low-cost, portable, and accurate I–V Curve Tracer (IVCT) for low-power solar photovoltaic (SPV) modules, capable of performing real-time performance evaluation directly in the field.

Overview
The system is based on an ESP32 microcontroller and uses a super-capacitor-based dynamic loading technique to trace I–V and P–V characteristics of small-scale SPV modules. It features automatic parameter extraction, high sampling accuracy, and quick characterization without the need for complex laboratory equipment.

Features
Portable and Low-Cost Design — Compact field-deployable setup using ESP32 and super-capacitive load.
Capacitor Loading Technique — Enables smooth voltage sweep from short-circuit to open-circuit conditions with minimal ripple.
Accurate Data Acquisition — Integrated current (ACS712) and voltage sensors for real-time measurement.
Onboard Display — OLED screen for live visualization of voltage, current, and power values.
Wireless Capability — Built-in Wi-Fi for remote data logging and cloud connectivity.
Energy-Efficient Operation — Entirely powered by solar input for off-grid field testing.

Hardware Components
ESP32 (NodeMCU) for control and data processing
Super-Capacitor Load for dynamic module characterization
ACS712 Current Sensor and voltage divider network
OLED Display for data visualization
Solar Panel (Low Power) under test

Software and Functionality
Programmed in Arduino IDE / ESP-IDF environment
Supports real-time plotting of I–V and P–V curves
Implements adaptive sampling for high-resolution data acquisition
Supports Python-based post-processing for parameter estimation and visualization

Results

The prototype successfully traced I–V curves of low-power SPV modules (up to 75 mA, 6 V) with high accuracy and minimal ripple. Field testing confirmed precise identification of maximum power points (MPP) and module efficiency under varying irradiance conditions.

Applications
Educational and research laboratories
Solar PV testing in field environments
DIY renewable energy experiments
Portable diagnostics for small solar modules

Future Scope
Integration of AI-based health diagnostics for PV modules
Web-based dashboard for real-time monitoring and data storage
Scalability for higher-power solar module characterization
