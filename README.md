# Embedded Systems & STM32 Masterclass 🚀

Welcome to the **Embedded Systems & STM32 Masterclass** repository! This project contains comprehensive, A-to-Z documentation and practical C code examples covering the core concepts of real-time embedded systems, hardware timers, serial communication, and FreeRTOS.

The content is provided as a single, beautifully styled, interactive HTML webpage alongside STM32 Hardware Abstraction Layer (HAL) code snippets.

---

## 📖 Table of Contents

1. [About the Project](#about-the-project)
2. [What You Will Learn](#what-you-will-learn)
3. [Included STM32 Projects](#included-stm32-projects)
4. [Getting Started](#getting-started)
5. [Prerequisites](#prerequisites)
6. [License & Credits](#license--credits)

---

## 💡 About the Project

This repository serves as both a theoretical textbook and a practical lab manual. It was generated from comprehensive course materials to bridge the gap between high-level embedded theory (like CPU scheduling and RTOS task states) and low-level microcontroller implementation using STMicroelectronics' ARM Cortex-M microcontrollers.

---

## 🧠 What You Will Learn

The documentation (`index.html`) is divided into four major theoretical sections:

* **Real-Time Operating Systems (RTOS):** Understand the difference between Super Loops and RTOS, task states, and inter-task communication (Queues, Mutexes, Semaphores).
* **Real-Time Systems:** Learn about Hard, Firm, and Soft real-time constraints, and dive into CPU scheduling algorithms (FCFS, RR, RM, EDF, LLF).
* **Hardware Timers:** Master the Time-Base Unit (Prescaler, Counter, Auto-Reload Register), SysTick, and advanced timer modes like PWM and Input Capture.
* **Serial Communication:** Deep dive into the wiring, architecture, and frame structures of **UART** (Asynchronous), **SPI** (Synchronous), and **I2C** (Synchronous).

---

## 🛠️ Included STM32 Projects

The documentation includes six complete, ready-to-use C code templates designed for STM32 microcontrollers using the HAL library. 

1.  **SysTick Blinky:** The "Hello World" of embedded systems using bare-metal delays.
2.  **Hardware Timer Interrupts:** Creating non-blocking time delays using General Purpose Timers (TIM3).
3.  **PWM Generation:** Fading an LED using Timer Output Compare registers.
4.  **UART Communication:** Transmitting via blocking polling and receiving via non-blocking interrupts.
5.  **SPI Master:** Synchronous full-duplex communication to read a sensor register.
6.  **FreeRTOS Integration:** A multi-tasking application demonstrating Producer/Consumer tasks communicating safely via RTOS Queues.

---

## 🚀 Getting Started

### Viewing the Documentation
1. Clone this repository to your local machine:
   ```bash
   git clone [https://github.com/yourusername/embedded-stm32-masterclass.git](https://github.com/yourusername/embedded-stm32-masterclass.git)
