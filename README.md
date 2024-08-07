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

 Ideally the output would look something like :
![image](https://github.com/user-attachments/assets/8d5469b1-56bd-4e45-94ee-eab0039f65a7)


## Quick Start

1. **Clone the Repo**: `git clone https://github.com/LakshmiNeithilath/ring-oscillator-with-PSpice.git`
2. **Open LTSpice**: Load `Ring_Oscillator.asc`.
3. **Run Simulation**: Use the settings above.
4. **Check Output**: Observe the waveform at node `Q`.

Happy simulating! 🚀
