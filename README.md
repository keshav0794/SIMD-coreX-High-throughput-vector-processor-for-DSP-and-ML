# SIMD-coreX-High-throughput-vector-processor-for-DSP-and-ML
The SIMD coreX project involves the design and verification of a high-throughput vector processor using SIMD (Single Instruction Multiple Data) architecture, implemented in Verilog HDL. The primary goal of the project is to enhance computational efficiency by exploiting data-level parallelism, making it suitable for applications in Digital Signal Processing (DSP) and Machine Learning (ML).

The processor architecture consists of a control unit, a vector register file, and a vector Arithmetic Logic Unit (ALU) composed of multiple parallel SIMD lanes. Each lane performs arithmetic operations such as addition, subtraction, and multiplication on 32-bit data elements. By employing a 4-lane SIMD structure, the processor can execute four operations simultaneously within a single clock cycle, significantly improving throughput compared to traditional scalar processors.

The instruction execution flow includes instruction decoding, parallel data processing, and result write-back to the register file. The design was modeled and simulated using Verilog, and its functionality was verified through testbench-based simulation and waveform analysis.

The project demonstrates the effectiveness of SIMD architecture in accelerating computation-intensive tasks such as matrix operations, filtering, and vector-based calculations. It also provides a foundational understanding of modern processor design techniques used in high-performance computing systems.
