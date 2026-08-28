## NOT Gate Implementation in SystemVerilog

A **NOT gate** (inverter) is a fundamental digital logic gate that implements logical negation. The output is always the complement of the input.

### Truth Table

| Input (A) | Output (Y) |
| :---: | :---: |
| 0 | 1 |
| 1 | 0 |

### Features
* Implemented using dataflow modeling (`assign` statement).
* Includes a self-checking testbench to verify outputs automatically.
* Generates a Value Change Dump (`.vcd`) file for waveform analysis.

### Waveform Verification
The testbench includes `$dumpfile` and `$dumpvars` commands to output a `dump.vcd` file. You can load this file into tools like **GTKWave** or **ModelSim** to visually verify the timing behavior.


###  waveform 
<img width="1871" height="458" alt="image" src="https://github.com/user-attachments/assets/cc2d79c6-6e60-483c-b0ef-70b749075b1f" />
