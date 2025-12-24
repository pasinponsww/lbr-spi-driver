# Bare-Metal SPI Driver (Flight Software)

This module provides a register-level SPI driver built for flight-software use — no HAL, no vendor libraries. The driver initializes SPI clocks and control registers, configures mode and chip-select behavior, and handles deterministic TX/RX transfers for hardware-in-the-loop testing and tightly-coupled embedded firmware workflows. Designed for reliability, repeatability, and full control over timing and bus behavior.
