# Traffic Light Controller - FSM-based 4-Way Traffic Control

**Brief:** A 4-way traffic light controller designed in Verilog using a Finite State Machine (FSM). Supports configurable timing for Green, Yellow, and Red phases for North-South and East-West directions. Validated with a self-checking testbench.

**Tools Used:** Verilog HDL, Icarus Verilog, GTKWave.

**Quick Run:**
```bash
iverilog -o traffic_sim traffic_light.v tb_traffic_light.v
vvp traffic_sim
gtkwave dump.vcd
