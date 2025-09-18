## Project Summary: Custom IoT PCB with ESP32-C3-02.

This project involves the design and development of a **4-layer custom PCB** for an IoT application powered by the ESP32-C3-02 SoC. The board integrates **Wi-Fi/BLE connectivity** and **TP4056-based Li-ion charging circuitry**, enabling efficient and safe charging of a single-cell Li-ion battery.

### Key Features

- **Microcontroller**: ESP32-C3-02 SoC with Wi-Fi and BLE connectivity  
- **Power Management**: TP4056 IC for single-cell Li-ion battery charging with thermal regulation  
- **Battery Protection**: Integrated under-voltage lockout and trickle charging  
- **Sensors and Modules**:  
  - BME280 for temperature, humidity, and pressure sensing  
  - Ambient light and sound sensors  
  - Mini SD card reader for local data storage  
  - Onboard flash memory for extended storage  
- **Display**: I2C OLED for real-time data visualization  
- **Power Inputs**:  
  - USB-C connector for charging and data transfer  
  - LiPo battery connector with onboard charging circuitry  
- **Indicators**: LED indicators showing charging and full-charge status  

### Design Highlights

1. **Power Supply Integration**  
   - USB-C powers both charging and system operation  
   - TP4056 manages charging and protection  
   - Regulated supply ensures ESP32-C3-02 stability  

2. **Modular Architecture**  
   - Supports multiple onboard sensors  
   - Expandable via additional I2C devices  

3. **Safe and Efficient Charging**  
   - Programmable charging current (external resistor)  
   - Automatic charge termination and built-in protection  

4. **Compact and Reliable Layout**  
   - Optimized **4-layer PCB routing** for minimal power loss  
   - Thermal management for TP4056 and critical components  

### Applications

- IoT edge devices for environmental monitoring  
- Low-power battery-operated data logging systems  
- Prototyping platform for ESP32-based IoT solutions  
