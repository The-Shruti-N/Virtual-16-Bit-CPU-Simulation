# Virtual-16-Bit-CPU-Simulation
Hardware simulation project building a custom 16 bit computer from nand gates using nandgame.com

This is to document my journey building a functional custom 16-bit computer from scratch starting from basic transistors/relays and primitive logic gates. I progressively built up combinational logic, arithmetic units, memory modules and a full cpu.

Step by step architecture and concepts:
- Logic gates: began by understanding physical switches to implement the fundamental nand gate and then built the standard gates using combinations of nand gates, and implemented multiplexers to route data signals based on control bits
- Arithmetic: progressed from half adders to full adders to multibit adders, built incrementers, subtractors, zero detectors and signs
- Switching and control: designed switching layers
- ALU: Combined logic units into a centralised processor core and used multiplexers to choose which operations output is sent
- Memory: built flip flops and registers and scaled up to ram
- CPU: integrated the components we made alr
In this manner i established the complete instruction execution cycle, enabling the computer to run programs.

What i learnt:
- gained an appreciation for how complex software abstractions rely entirely on voltage states


disclaimer: i promise i didnt etch silicon in my room, this was done on a heavily abstracted platform :3 
