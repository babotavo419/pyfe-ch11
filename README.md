# pyfe-ch11
Extracting Data With Regular Expressions
ThIn this assignment you will read through and parse a file with text and numbers. You will extract all the numbers in the file and compute the sum of the numbers.
this is my code -
import re

handle = open("regx_sum_1632147.txt")
sum = 0
for line in handle:
    nums = re.findall('[0-9]+',line)
    
    length = len(num)
    for i in range(length):
        sum += int(num[i])

print(sum)

when I run it the is the error

>>> ch11_ex1.py
Traceback (most recent call last):
  File "<stdin>", line 1, in <module>
NameError: name 'ch11_ex1' is not defined
>>> 

I've also tried it this way

>>> python3 ch11_ex1.py
  File "<stdin>", line 1
    python3 ch11_ex1.py
            ^^^^^^^^
SyntaxError: invalid syntax
>>> 
if someone could help that would be great
