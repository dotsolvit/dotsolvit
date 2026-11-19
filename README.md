# Hi there, I'm Oleksandr 👋

I am an embedded software engineer passionate about hardware, software, and building reliable, lightweight applications. My primary focus is on developing automation systems based on STM32, ESP32, and ATMega, robotics, smart home integration, and deploying AI models onto edge computing devices like the Raspberry Pi 5.

I combine firmware development with hands-on hardware debugging using digital oscilloscopes and logic analyzers.


---

### 🛠️ Tech Stack & Tools

* **Languages:** C, C++, Python, JavaScript (Basics), HTML/CSS
* **Microcontrollers & SBCs:** STM32(Cortex-M), ESP32, ESP8266, ATmega2560, ATmega328, Raspberry Pi 5
* **Interfaces & Protocols:** UART, I2C, SPI, MQTT (Mosquitto), JSON
* **IDEs & Toolchains:** STM32CubeIDE (+ CubeMX), Keil uVision5 (Arm Compiler 6), VS Code (+ PlatformIO), Arduino IDE
* **Hardware & EDA:** EasyEDA (Schematics & PCB), Digital Oscilloscope (OWON SDS210S), Logic Analyzers, THT/SMD soldering
* **Tools & OS:** Git, GitHub, Linux (CLI, Admin, Bash Scripting), Raspberry Pi OS, Windows


---

### 🚀 Highlighted Project

📌 **[STM32F1-smartUGV-RPi5-Astar](https://github.com)**
An autonomous unmanned ground vehicle (UGV) featuring distributed control architecture, sensor fusion, dynamic obstacle avoidance, and A* path planning.
* **Real-Time Firmware (STM32F103):** Built a non-blocking state-machine architecture (HAL + direct register access) handling 4-channel PWM motor control (DRV8833), servo scanning (TIM1), hardware input-capture odometry (TIM3), and microsecond integration (TIM2).
* **Sensor Fusion & Calibration:** Combined MPU6050 gyroscope (50 Hz) and HP5883 magnetometer (10 Hz) via a complementary filter with 0°/360° wrap-around handling and automated Hard-Iron calibration saved to internal Flash.
* **Custom Binary UART Protocol:** Designed a fault-tolerant, zero-overhead binary protocol (`CRC8` verified) bridging STM32, an ESP32-CAM MQTT gateway, and a Raspberry Pi 5 navigation server.


📌 **[stm32-nonblocking-firmware-template](https://github.com/dotsolvit/stm32-nonblocking-firmware-template)**
A production-grade, event-driven firmware template for the STM32F103 (Cortex-M3) showing an efficient bare-metal architecture.
* Implemented a completely **non-blocking main loop** scheduler via SysTick, cutting out all blocking delays.
* Offloaded ISRs with asynchronous callback interlocking: EXTI-triggered ADC sampling and a fast **20-byte UART Ring Buffer**.
* Embedded low-level Flash memory operations (page erasing/half-word writing) and custom UART/Flash hardware error handling.

📌 **[stm32f0-gpio-speed-comparison](https://github.com/dotsolvit/stm32f0-gpio-speed-comparison)**
A hardware-verified benchmark analyzing ST HAL library overhead vs. direct register access (CMSIS).
* Measured a **14.5x** execution speed difference under `-O0` using an **OWON SDS210S** oscilloscope.
* Captured and analyzed hardware artifacts like **compiler loop unrolling** and **Flash prefetch buffer stalls** at 48 MHz.

📌 **[esp32-c6-low-power-weather-station](https://github.com/dotsolvit/esp32c6-iot-weather-station)**
An energy-efficient low-power IoT weather station monitoring environmental data.
* Transmits sensor data via MQTT (JSON format) to a local server.
* Integrated into a custom **Home Assistant Core** instance running on Raspberry Pi 5.


---

📬 **How to reach me:** Connect with me on [LinkedIn](https://www.linkedin.com/in/oleksandrdotsenko/)


