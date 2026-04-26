COMPANY: CODTECH IT SOLUTIONS

NAME: POTHURAJU PRAKASH

INTERN ID: CTIS3676

DOMAIN: VLSIRATION

DURATION: 6 MONTHS

MENTOR: NEELA SANTOSH KUMAR

Here’s a **500+ word professional description** of your EPWave simulation waveform that you can use in your report or GitHub:

---

## 📊 EPWave Simulation Waveform Description

The waveform shown above represents the simulation results of a **4-bit Arithmetic Logic Unit (ALU)** designed using Verilog HDL and executed in an online simulation environment. The waveform is generated using the EPWave viewer, which visually illustrates how input signals and corresponding outputs change over time. This graphical representation is crucial for verifying the functional correctness of the ALU design.

The signals displayed in the waveform include the input operands **A[3:0]** and **B[3:0]**, the selection control signal **sel[2:0]**, and the output signals **result[3:0]** and **carry**. The simulation is structured in discrete time intervals, where each interval corresponds to a specific operation selected by the control signal.

Initially, the inputs are set as A = 0101 (decimal 5) and B = 0011 (decimal 3), and these values remain constant throughout the simulation. The variation in output is driven entirely by changes in the **sel** signal, which determines the operation performed by the ALU.

At the first time interval, the selection signal is **000**, which corresponds to the addition operation. The ALU computes the sum of A and B, resulting in **1000 (decimal 8)**. The carry output is **0**, indicating that no overflow occurred during the addition. This confirms the correct implementation of the addition logic.

In the next interval, the selection signal changes to **001**, representing subtraction. The ALU performs A − B, yielding **0010 (decimal 2)**. Again, the carry remains **0**, showing that no borrow condition affected the output. The waveform clearly shows the transition in the result signal corresponding to this operation.

When the selection signal is updated to **010**, the ALU performs a bitwise AND operation between A and B. The output becomes **0001**, which is the correct result of the AND operation between 0101 and 0011. The carry signal remains inactive (0), as expected for logical operations.

Subsequently, when the selection signal is **011**, the ALU executes a bitwise OR operation. The result is **0111**, which accurately reflects the OR combination of the input operands. The waveform demonstrates a clear and stable transition to this value, validating the logical OR functionality.

Finally, when the selection signal is set to **100**, the ALU performs a NOT operation on input A. The result is **1010**, which is the bitwise inversion of 0101. This confirms that the unary operation is correctly implemented in the design. The carry signal remains 0, as it is not relevant for this operation.

Throughout the waveform, the signals are stable within each time interval and transition cleanly at the boundaries, indicating proper combinational logic behavior without glitches. The consistency between expected theoretical results and simulated outputs confirms that the ALU design is functionally correct.

In conclusion, the EPWave simulation waveform effectively demonstrates the correct working of all implemented ALU operations. It serves as a visual validation tool, ensuring that the design meets its intended functionality and adheres to digital design principles.

 OUTPUT:
 <img width="1700" height="925" alt="Image" src="https://github.com/user-attachments/assets/da60d1e5-bf88-403c-ac5a-f79cbd9e5488" />


