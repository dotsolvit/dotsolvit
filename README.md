# Hi there, I'm Oleksandr 👋

I am an embedded software engineer passionate about hardware, software, and building reliable, lightweight applications. My primary focus is on developing automation systems based on STM32, ESP32, and ATMega, robotics, smart home integration, and deploying AI models onto edge computing devices like the Raspberry Pi 5.

I combine firmware development with hands-on hardware debugging using digital oscilloscopes and logic analyzers.


---

### 🛠️ Tech Stack & Tools

* **Languages:** C, C++, Python, JavaScript (Basics), HTML/CSS
* **Microcontrollers & Single-Board Computers:** STM32(Cortex-M), ESP32, ESP8266, ATmega2560, ATmega328, Raspberry Pi 5
* **Interfaces & Protocols:** UART, I2C, SPI, MQTT (Mosquitto), JSON
* **IDEs & Ecosystems:** STM32CubeIDE (+ CubeMX), Keil uVision5 (Arm Compiler 6), VS Code (+ PlatformIO), Arduino IDE
* **Hardware Design (EDA):** EasyEDA (Schematics & PCB), Digital Oscilloscope (OWON SDS210S), Logic Analyzers, THT/SMD soldering
* **Tools & OS:** Git, GitHub, Linux (CLI, Admin, Bash Scripting), Raspberry Pi OS, Windows


---

### 🚀 Highlighted Project

📌 **[stm32f0-gpio-speed-comparison](https://github.com/dotsolvit/stm32f0-gpio-speed-comparison)**
A hardware-verified benchmark analyzing ST HAL library overhead vs. direct register access (CMSIS).
* Measured a **14.5x** execution speed difference under `-O0` using an **OWON SDS210S** oscilloscope.
* Captured and analyzed hardware artifacts like **compiler loop unrolling** and **Flash prefetch buffer stalls** at 48 MHz.

📌 **[rpi5-ai-english-tutor](https://github.com/dotsolvit/rpi5-ai-english-tutor)**
An asynchronous Telegram bot running 24/7 on a Raspberry Pi 5 that acts as a spoken English tutor. 
* Fully async audio pipeline using system `ffmpeg` (Python 3.13+ compatible).
* Built-in token budget tracking and cumulative logging.

📌 **[esp32-c6-low-power-weather-station](https://github.com/dotsolvit/esp32c6-iot-weather-station)**
An energy-efficient low-power IoT weather station monitoring environmental data.
* Transmits sensor data via MQTT (JSON format) to a local server.
* Integrated into a custom **Home Assistant Core** instance running on Raspberry Pi 5.


---

📬 **How to reach me:** Connect with me on [LinkedIn](https://www.linkedin.com/in/oleksandrdotsenko/)


