# Python Lab Assignment

**Name:** Taha Ahmad

This repository has five Python programs for my lab assignment. They cover functions, loops, conditions, strings, lists, dictionaries and saving results in text files.

## sentence.py

This program takes a sentence and finds the number of words, characters and vowels. Spaces are also included in the character count.

`split()` separates the words. `max()` and `min()` find the longest and shortest words by comparing their lengths. A set keeps the unique words in lowercase, and `sorted()` puts them in alphabetical order. If the input has no words, the program asks for a valid sentence and stops.

The results appear on the screen and are saved in `word_analysis.txt`. For example, `Learning Python is fun` has 4 words and 6 vowels.

## menu.py

This is a restaurant ordering program. The menu has burgers, pizza, fries and drinks. The item names and prices are stored in a dictionary.

The user selects an item and enters its quantity. Each order is added to a list, and the menu keeps appearing until the user selects option 5. The program checks that the quantity is greater than zero.

`calculate_bill()` adds the order totals. For example, 2 burgers and 1 fries cost Rs. 1,250. The final bill is displayed and saved in `orders.txt`.

## calculator.py

The calculator takes two numbers and an operation. It has separate functions for addition, subtraction, multiplication, division and modulus.

Conditions decide which function to call. For division and modulus, the program checks that the second number is not zero. For example, entering 10, 2 and `+` gives 12.0.

After each calculation, the user can enter `yes` to continue. Any other answer closes the program.

## bill.py

This code takes the name, price and quantity of five products. Each product is stored in a dictionary, and the dictionaries are kept in a list.

The total for each product is its price multiplied by its quantity. These totals are added to calculate the complete bill. A 10% discount is given when the bill is greater than Rs. 10,000.

It also finds the product with the highest unit price. The bill, discount and final amount are displayed and saved in `bill.txt`. For a bill of Rs. 10,850, the final amount is Rs. 9,765.

## result.py

This program calculates results for five students. It takes a student's name, roll number and marks in Python, AI and Mathematics.

The three marks are added to get the total. The percentage is calculated by dividing the total by 3, assuming each subject is out of 100. Conditions assign the grade:

| Percentage | Grade |
| --- | --- |
| 80 or above | A |
| 70 to below 80 | B |
| 60 to below 70 | C |
| 50 to below 60 | D |
| Below 50 | Fail |

Each result is stored in a dictionary. The program displays all five results and finds the student with the highest percentage. The individual results are saved in `result.txt`.

For example, marks of 80, 80 and 80 give a total of 240, a percentage of 80% and grade A.

## Running the files

Python 3 is needed. Open a terminal in the folder containing the files and run the program you want:

```bash
python sentence.py
python menu.py
python calculator.py
python bill.py
python result.py
```

Run one command at a time and enter the values requested. On Windows, `py` can be used instead of `python`.

Enter numbers at numeric prompts; letters will cause an error. The text reports are saved in the working folder and replaced when the same program is run again.
