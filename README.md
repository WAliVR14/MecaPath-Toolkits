# ⚙️ MecaPath Engineering Toolkits

*Read this in [Spanish (Español)](#-versión-en-español)*

**Software, Frameworks & HDL**
<br>
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![C](https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white)
![Verilog](https://img.shields.io/badge/Verilog-003C66?style=for-the-badge&logoColor=white)
![VHDL](https://img.shields.io/badge/VHDL-0A3366?style=for-the-badge&logoColor=white)
![ROS2](https://img.shields.io/badge/ROS2-22314E?style=for-the-badge&logo=ros&logoColor=white)

**Hardware & Embedded Systems**
<br>
![ESP32](https://img.shields.io/badge/ESP32-E7352C?style=for-the-badge&logo=espressif&logoColor=white)
![STM32](https://img.shields.io/badge/STM32-03234B?style=for-the-badge&logo=stmicroelectronics&logoColor=white)
![Arduino](https://img.shields.io/badge/Arduino-00979D?style=for-the-badge&logo=arduino&logoColor=white)
![Raspberry Pi](https://img.shields.io/badge/Raspberry%20Pi-C51A4A?style=for-the-badge&logo=raspberry-pi&logoColor=white)
![FPGA](https://img.shields.io/badge/FPGA-FF4F00?style=for-the-badge&logo=circuit-board&logoColor=white)

**Electronic Design & Simulation (EDA)**
<br>
![KiCad](https://img.shields.io/badge/KiCad-314CB6?style=for-the-badge&logo=kicad&logoColor=white)
![LTspice](https://img.shields.io/badge/LTspice-FF6600?style=for-the-badge&logo=analog-devices&logoColor=white)
![Wokwi](https://img.shields.io/badge/Wokwi-2D2D2D?style=for-the-badge&logoColor=white)

Welcome to the official **MecaPath** repository. Here you will find the source code, simulations, and algorithms developed on the channel, designed to automate and solve complex mechatronics engineering problems.

## 📂 Repository Structure

| Episode | Topic | Tools | Code Link |
| :--- | :--- | :--- | :--- |
| **EP01** | Automated Mesh Analysis | Python, SymPy | [View Project](./EP01_Automated_Mesh_Analysis) |
| **EP02** | Kalman Filter for IMU MPU6050 | C++, FreeRTOS | [View Project](./EP02_Kalman_Filter) |

## 🚀 Usage and Execution Guidelines

Given the multidisciplinary nature of mechatronics, each episode folder contains its specific execution environment. Please follow the standard procedures below based on the project type:

*   **🐍 Python (Math & Automation):** It is highly recommended to run the `.ipynb` files using the provided **Google Colab** links to avoid dependency issues. For local execution, initialize a virtual environment (`venv`) and install the `requirements.txt` file.
*   **⚡ C / C++ (Embedded Firmware):** Microcontroller projects (ESP32, STM32, Arduino) are structured for **PlatformIO** (VS Code) or **CMake**. Do not compile directly via GCC without checking the `.ini` configuration files.
*   **🤖 ROS2 (Robotics):** Workspaces (`src`) must be built using `colcon build` within a sourced ROS2 environment (Humble/Iron) on Ubuntu or a Docker container.
*   **🛠️ HDL (FPGA):** Hardware description projects (Verilog/VHDL) include configuration files for **Gowin EDA** or testbenches for simulation with Icarus Verilog.
*   **📐 EDA & Simulation:** Schematic files (`.kicad_sch`), PCB layouts (`.kicad_pcb`), and circuit simulations are designed to be opened with the latest stable versions of **KiCad** or **LTspice**, respectively.

---

## 🇪🇸 Versión en Español

Bienvenido al repositorio oficial de **MecaPath**. Aquí encontrarás todo el código fuente, simulaciones y algoritmos desarrollados en el canal, diseñados para automatizar y resolver problemas complejos de ingeniería mecatrónica.

### 📂 Estructura del Repositorio

| Episodio | Tema | Herramientas | Enlace al Código |
| :--- | :--- | :--- | :--- |
| **EP01** | Análisis de Mallas Automatizado | Python, SymPy | [Ver Proyecto](./EP01_Automated_Mesh_Analysis) |
| **EP02** | Filtro Kalman para IMU MPU6050 | C++, FreeRTOS | [Ver Proyecto](./EP02_Kalman_Filter) |

### 🚀 Guía de Uso y Ejecución

Dada la naturaleza multidisciplinaria de la mecatrónica, cada carpeta contiene su entorno de ejecución específico. Sigue estos procedimientos estándar según el tipo de proyecto:

*   **🐍 Python (Matemáticas y Automatización):** Se recomienda ejecutar los archivos `.ipynb` utilizando los enlaces de **Google Colab** proporcionados para evitar problemas de dependencias. Para uso local, inicializa un entorno virtual (`venv`) e instala el archivo `requirements.txt`.
*   **⚡ C / C++ (Firmware Embebido):** Los proyectos para microcontroladores (ESP32, STM32, Arduino) están estructurados para **PlatformIO** (VS Code) o **CMake**. No compiles directamente con GCC sin revisar los archivos de configuración `.ini`.
*   **🤖 ROS2 (Robótica):** Los espacios de trabajo (`src`) deben compilarse utilizando `colcon build` dentro de un entorno ROS2 configurado (Humble/Iron) en Ubuntu o Docker.
*   **🛠️ HDL (FPGA):** Los proyectos de descripción de hardware (Verilog/VHDL) incluyen archivos de configuración para **Gowin EDA** o *testbenches* para simulación con Icarus Verilog.
*   **📐 EDA y Simulación:** Los esquemáticos (`.kicad_sch`), diseños de placas (`.kicad_pcb`) y simulaciones de circuitos están diseñados para abrirse con las últimas versiones estables de **KiCad** o **LTspice**.
