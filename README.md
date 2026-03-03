📌 Project Overview

This project demonstrates a PLC-based conveyor motor control system developed using Ladder Logic. The system includes safety fault memory, manual reset logic, and sensor-triggered delayed stop functionality.

⚙️ Key Features

Start/Stop self-holding motor control

Emergency fault latch using Set/Reset structure

Manual reset requirement after fault condition

Sensor-triggered 3-second delayed stop using TON timer

Clean ladder structure without double coil conflicts

🛠️ Technologies & Tools

Software: GMTSuite

Language: Ladder Logic (LAD)

Concepts Used: Memory Bits, Set/Reset Latch, TON Timer, Interlocking Logic, Self-Holding Circuit

🚀 System Operation

Operator presses the Start button → motor latches and runs.

If sensor detects a product while motor is running, a 3-second TON timer starts.

After timer completion, motor stops automatically.

If Emergency is pressed, a fault memory bit is set.

System remains locked until Reset is pressed.
### 1. System Active & Motor Running
![System Active](Ekran%20görüntüsü%202026-03-03%20232521.png)

### 2. Sensor Triggered & Timer Counting
![Timer Counting](Ekran%20görüntüsü%202026-03-03%20232600.png)

### 3. Motor Restarted Automatically
![Motor Restart](Ekran%20görüntüsü%202026-03-03%20232618.png)
