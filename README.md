# Fermats-little-theorem
This simple python code checks a number if it is a prime number following the discovery of Fermat.

## Usage
python check_prim.py {number} [fast](optional)

- python check_prim.py {number} -> checks the number against all bases of a which eliminates false-positive outputs, like the carmichael numbers (561, 1105, 1729, ...).

- python check_prim.py {number} fast -> will only check against a = 2, which can result in false-positive outputs, but is blazingly faster with big numbers for like rsa.
