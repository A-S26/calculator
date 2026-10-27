This is a readme for the plan of a calculator in python.
A Python 3 calculator used from the Terminal, built in the SCCM4910 DevOps labs.

what the calculator will be able to do:

Add, subtract, multiply and divide two numbers; display the result.

how to run the calculator:

Run: python3 calculator.py
Enter the first number, operator (+ - * /), then second number.
The program prints Result: followed by the answer.

#!/bin/bash
set -e
cd -- "$(dirname -- "$0")"
python3 calculator.py

