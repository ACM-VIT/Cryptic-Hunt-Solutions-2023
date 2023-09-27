
# Cracking the Grid Code

**Category:** Medium  
**Mode:** Hybrid  
**Authors:** Raghav Ravishankar, Palak Jethwani, Adarsh Arunkumar  
**Specifications:**  
- **Entry point:** Visual grid  
- **Reward:** TBD

## Description

Can you decode the cryptic visual grid? In this puzzle, you're presented with a series of columns, each column containing a set of symbols: blank, circle, or square.

Your mission, should you choose to accept it, is to decipher the grid and uncover the hidden message.

## Solution

**Step 1:**  
Firstly, understand the encoding mechanism. Each vertical set of three symbols corresponds to a number. The representation is:
- Blank = 0
- Circle = 1
- Square = 2

These are ternary numbers.

**Step 2:**  
Convert these ternary numbers into base 10. For example, if you have the sequence 120 (with 1 as Circle, 2 as Square, and 0 as Blank), the conversion will be done by the formula:

\[
(A)3^2 + (B)3^1 + (C)3^0
\]

For 120, this becomes:

\[
(1)3^2 + (2)3^1 + (0)3^0 = 15
\]

This number represents the 15th letter of the alphabet, i.e., O.

**Step 3:**  
By decoding each column in the grid using the method above, you'll unveil the hidden message: "Technology Tower."

**Final Step:**  
The decoded message "Technology Tower" is the final answer that you submit

## Hints

1. Consider the shapes and their edges: Blank (0 edges), Circle (1 edge), Square (4 edges). Does the sequence remind you of a number system?
2. Once the numbers are clear, remember the basics of letter-number correspondence in the alphabet.


