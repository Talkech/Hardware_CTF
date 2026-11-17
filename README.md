# Hardware CTF Board

A custom PCB used as a hardware capture the flag challenge for those who wants to learn get into hardware hacking.

The goal is to recover a flag from each stage using real hardware-hacking techniques, then submit it over a serial console. Each solved stage lights an LED, updates a score counter, and displays a message and the score on an OLED display.

*Board:* STM32F103C8T6, 2-layer

## Stages

1. Hidden UART console (Finding unlabelled pads, identifying the baud rate)
2. SPI flash dump
3. I2C bus sniffing (Capturing and decoding a bus with a logic analyser)
4. Firmware reverse engineering (Static analysis of an ARM binary)
5. SWD debug access (Halting the core and reading memory)
6. RF capture & replay (SDR capture and retransmission at 433MHz)
7. Timing side-channel (Exploiting a non-constant-time comparison)

## Status
- [x] Schematic
- [x] PCB layout
- [ ] Firmware
- [ ] Fabrication & assembly

## Author

Talkech