# Embedded Systems Course – STM32 Projects

This repository contains step-by-step application projects (gomuluders1–gomuluders23) prepared as part of an **STM32-based embedded systems course**. Each folder represents a lesson/lab session and aims to teach a specific peripheral or embedded systems concept.

Projects are developed using **STM32CubeIDE** and **HAL libraries**.

---

## Requirements

* STM32CubeIDE
* STM32 development board (commonly STM32F1 / STM32F4 series)
* ST-Link (on-board or external)
* Basic knowledge of C programming and embedded systems

---

## Project Structure

Each project generally follows the structure below:

```
Core/
 ├── Inc/
 └── Src/main.c
Drivers/
STM32CubeIDE project files
```

The main application code is located in:

```
Core/Src/main.c
```

---

## Project List & Descriptions

### gomuluders1 – LED Blink

Basic LED blinking application using GPIO on STM32F4.

### gomuluders2 – LED & Button

LED control using a push button on STM32F4.

### gomuluders3 – External Interrupt (EXTI)

Using external interrupts (EXTI) triggered by a button on STM32F4.

### gomuluders4 – ADC Polling Method

Reading analog data using the ADC peripheral with polling method on STM32F4.

### gomuluders5 – ADC Interrupt Method

ADC data acquisition using interrupt-based method on STM32F4.

### gomuluders6 – ADC DMA (2 Potentiometers)

Continuous ADC data reading from two potentiometers using DMA on STM32F4.

### gomuluders7 – Timer Interrupt Method

Using timer interrupts to perform periodic tasks on STM32F4.

### gomuluders8 – Timer PWM Mode

PWM signal generation and control using timer PWM mode on STM32F4.

### gomuluders9 – DAC Normal Mode

Generating analog output using the DAC peripheral in normal mode on STM32F4.

### gomuluders10 – DAC Sine Wave

Sine wave generation using DAC on STM32F4.

### gomuluders11 – DAC Triangle Wave & Noise

Triangle wave and noise signal generation using DAC on STM32F4.

### gomuluders12 – UART Polling Mode (Transmit)

UART data transmission using polling method on STM32F4.

### gomuluders13 – UART Polling Mode (Receive)

UART data reception using polling method on STM32F4.

### gomuluders15 – UART DMA Mode

High-efficiency UART communication using DMA on STM32F4.

### gomuluders16 – Touch Sensor Usage

Using a capacitive touch sensor with STM32F4.

### gomuluders17 – PIR Sensor Usage

Motion detection application using a PIR sensor on STM32F4.

### gomuluders18 – Delay Generation

Creating delays using SysTick or timers on STM32F4.

### gomuluders19 – Joystick Usage

Reading joystick inputs (analog/digital) using STM32F4.

### gomuluders20 – Rotary Encoder Usage

Position and direction detection using a rotary encoder on STM32F4.

### gomuluders21 – Laser-Based Alarm System

Designing a simple laser-based alarm system using STM32F4.

### gomuluders22 – Tilt Switch Usage

Using a tilt switch (inclination sensor) with STM32F4.

### gomuluders23 – Random Number Generator

Using the hardware random number generator (RNG) peripheral on STM32F4.

---

## Build & Run

1. Open **STM32CubeIDE**
2. Go to **File > Import > Existing Projects into Workspace**
3. Select the desired `gomuludersX` folder
4. Verify pin assignments and clock configuration
5. Build the project and flash it to the board

---

## Educational Notes

* Projects are ordered from beginner to advanced level
* Each lesson focuses on a single core concept
* Code is written in a clear and educational manner

---

## License

This repository is intended for educational use only.

---

Author: Embedded Systems Course xBowtie

