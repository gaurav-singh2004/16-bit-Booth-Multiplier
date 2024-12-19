<h1>Booth Multiplier Project</h1>

<h2>Overview</h2>
<p>This project implements a Booth multiplier, a binary multiplication algorithm that uses Booth's algorithm for signed binary multiplication. It is a significant algorithm in digital signal processing and computer arithmetic.</p>

<h2>Features</h2>
<ul>
    <li>Booth's Algorithm Implementation: The core logic of the Booth algorithm to perform multiplication of two binary numbers.</li>
    <li>User-Friendly Interface: Inputs are provided in binary form, and the output is also displayed in binary.</li>
    <li>Simulation in Xilinx Vivado: The design has been simulated using Xilinx Vivado for validation and testing.</li>
</ul>

<h2>Modules </h2>
<ul>
    <li><strong>XOR Module:</strong> A basic XOR gate used to perform binary addition and subtraction operations within the multiplier logic.</li>
    <li><strong>Full Adder Module:</strong> Implements the full adder logic required for binary addition in the Booth multiplier, handling carry operations.</li>
    <li><strong>Eight-bit Adder/Subtractor Module:</strong> Computes the sum and difference of 8-bit binary numbers. This module is used for generating partial products and handling two’s complement when necessary.</li>
    <li><strong>Booth Substep Module:</strong> Implements the substeps of Booth’s algorithm, including encoding the multiplier and handling shifts during the multiplication process.</li>
    <li><strong>Booth Multiplier Module:</strong> The core logic that brings together all modules to perform the Booth multiplication process. It calculates the product of two 8-bit binary numbers using Booth’s algorithm.</li>
    <li><strong>Testbench:</strong> A simulation environment designed to validate the Booth multiplier design. It provides a set of test cases to verify the correctness of the multiplier by comparing its output with expected results. The testbench uses Xilinx Vivado for simulation and includes various binary input combinations to test the multiplication logic.</li>
</ul>
