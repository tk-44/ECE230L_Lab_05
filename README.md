# Lab 05 - Combinatorial Logic

In this lab, you’ve learned real world applications of digital logic, as well
as how to assemble your own Verilog modules. In addition, you’ve learned how
the constraints file maps your inputs and outputs to real pins on the FPGA.

## Rubric

| Item | Description | Value |
| ---- | ----------- | ----- |
| Summary Answers | Your writings about what you learned in this lab. | 25% |
| Question 1 | Your answers to the question | 25% |
| Question 2 | Your answers to the question | 25% |
| Question 3 | Your answers to the question | 25% |

## Name
Tanner Klinge & Damian Skeen
## Lab Summary
Today we implemented two different circuits into verilog and combined them in a top file using instances and a wire to connect the circuits. We found the minterms using K-maps for each circuit, and implemented them into corresponding files. Explored the contriants file and learned how they connect switches and leds properly. 
## Lab Questions

### 1 - Explain the role of the Top Level file.
- connects both of circuits into one file using instances, assigning both led and switch number.
### 2 - Explain the function of the Constraints file.
- ensures switches and leds are connected correctly, and corresponding with the nessecary file.
### 3 - Was the selection of Minterm and Maxterm correct for each circuit? What would you have chosen?
- We choose minterms for both circuits becuase they grouped the easist. ensuring minimal cost on our design. 
