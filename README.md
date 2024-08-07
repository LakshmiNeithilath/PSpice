# Ring Oscillator LTSpice Simulation

Welcome! This repo includes an LTSpice simulation for a ring oscillator, a key component in generating oscillating signals in digital circuits.

## What is a Ring Oscillator?

A **ring oscillator** is a circuit made of an odd number of inverters connected in a loop. It generates a continuous oscillating signal. Its simplicity and ability to produce precise frequencies make it invaluable in electronics and testing.

## Simulation Details

- **WL Pulse Source**: `PWL(0 850m 2.49n 850m 2.5n 0 3n 0 3.01n 0 3.02n 850m)`
- **BL Voltage Source**: `PULSE(850m 0 0 10p 10p 490p 1n)`
- **Stop Time**: 8n (8 nanoseconds)
- **Time Step**: 1p (1 picosecond)
- **Output Node**: `Q`

### Files

- **Schematic**: [Ring_Oscillator.asc](./Ring_Oscillator.asc)
- **Simulation File**: [Ring_Oscillator.sim](./Ring_Oscillator.sim)
