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
Aaron Easterday
Daniel Toronto

## Lab Summary
We used our existing knowledge of K-maps, truth tables, and boolean logic to build our knowledge of verilog code. We built two circuits and used code to make the output of circuit A an input to circuit B.

## Lab Questions

### 1 - Explain the role of the Top Level file.
The top level file takes code that we wrote for each circuit and assigns it to switches and leds allowing us to combine the circuits.

### 2 - Explain the function of the Constraints file.
The constraint file estalishes which switches and LEDs are available to be used.

### 3 - Was the selection of Minterm and Maxterm correct for each circuit? What would you have chosen?
Minterms would have been more efficient for circuit A because there were significantly more zeros than ones. This made our use of maxterms for this circuit very inefficient. Additionally, maxterms would have been more efficient for circuit B because it would have allowed us to use less groupings in our K-map.
