# Stage 19: Embedded and Hardware Programming (Projects 353-368)

**Learning Goal**: Program close to hardware

## C17: **GPIO Pin Control Simulator**

- **Description**: Create GPIO simulator showing: pin direction setting (input/output), digital read/write operations, pull-up/pull-down configuration, pin state visualization, and hardware abstraction layer.
- **Prerequisites**: LB67, UB67
- **New Concept**: GPIO control

## C18: **LED Pattern Controller**

- **Description**: Build LED control system: blink patterns, PWM brightness control, multi-LED sequences, pattern storage/playback, and timing precision management.
- **Prerequisites**: C17, UB38
- **New Concept**: LED control

## C19: **Sensor Reading Interface**

- **Description**: Implement sensor interfaces for: analog value simulation, digital sensor reading, threshold detection, averaging/filtering, and calibration routines.
- **Prerequisites**: C17, TB57
- **New Concept**: Sensor interfacing

## C20: **PWM Signal Generator**

- **Description**: Create PWM controller: duty cycle adjustment, frequency control, software PWM implementation, hardware timer usage concepts, and servo motor control.
- **Prerequisites**: C18, UB86
- **New Concept**: PWM generation

## C21: **Interrupt Service Simulator**

- **Description**: Build interrupt handling system: ISR registration, interrupt priorities, nested interrupts, interrupt latency measurement, and critical section protection.
- **Prerequisites**: UB36, C17
- **New Concept**: Interrupt handling

## C22: **Hardware Timer Programming**

- **Description**: Develop timer applications: periodic interrupts, one-shot timers, timer cascading, precise delays, and real-time clock simulation.
- **Prerequisites**: C21, UB38
- **New Concept**: Hardware timers

## C23: **UART Serial Communication**

- **Description**: Implement UART interface: baud rate configuration, data transmission/reception, parity/stop bits, flow control, and terminal emulator.
- **Prerequisites**: C2, C15
- **New Concept**: Serial communication

## C24: **SPI Interface Protocol**

- **Description**: Create SPI communication: master/slave roles, clock polarity/phase, multi-slave selection, data exchange protocols, and device simulation.
- **Prerequisites**: C23, UB67
- **New Concept**: SPI protocol

## C25: **I2C Protocol Implementation**

- **Description**: Build I2C system showing: start/stop conditions, addressing, clock stretching, multi-master concepts, and EEPROM communication simulation.
- **Prerequisites**: C24
- **New Concept**: I2C protocol

## C26: **ADC/DAC Interface**

- **Description**: Develop analog interfaces: ADC reading simulation, resolution/sampling rate, DAC output generation, signal conditioning, and waveform generation.
- **Prerequisites**: C19, UB69
- **New Concept**: Analog conversion

## C27: **Watchdog Timer System**

- **Description**: Implement watchdog timer: timeout configuration, watchdog reset, failure detection, system recovery, and reliability improvement demonstration.
- **Prerequisites**: C22, UB79
- **New Concept**: Watchdog timers

## C28: **DMA Controller Concepts**

- **Description**: Simulate DMA operations: memory-to-memory transfer, peripheral DMA, circular buffers, transfer completion notification, and CPU offloading benefits.
- **Prerequisites**: MB7, C21
- **New Concept**: DMA programming

## C29: **Real-Time Task Scheduler**

- **Description**: Build basic RTOS concepts: task creation, priority scheduling, preemption, context switching simulation, and deadline monitoring.
- **Prerequisites**: UB79, C21
- **New Concept**: RTOS basics

## C30: **Power Management System**

- **Description**: Create power control: sleep mode entry/exit, wake-up sources, power consumption tracking, battery level simulation, and low-power strategies.
- **Prerequisites**: UB86, C27
- **New Concept**: Power management

## C31: **Bootloader Simulator**

- **Description**: Implement boot concepts: startup code, memory initialization, application loading, firmware update simulation, and boot sequence display.
- **Prerequisites**: MB52, C27
- **New Concept**: Bootloader design

## C32: **TEST: IoT Device Controller**

- **Description**: Build complete IoT device with: sensor data collection system, actuator control (LED/motor), communication protocol (UART/I2C), power management features, real-time constraints handling, interrupt-driven architecture, configuration storage, and diagnostic capabilities.
- **Prerequisites**: C17-C31
- **New Concept**: Embedded integration
