# Python Week 4 Assessed Workshop

Work in CodeSpaces. 

If CodeSpaces does not load after 5 mins (like last week) open JupyterLab and add your answers to the below exercises in a single notebook.

You may use the following cheat sheets if you need to look up any Python commands.

https://github.com/phil-lewis-exe/PythonCheatSheets

You should not need to use any other websites. 

---

## TASKS


### Part 1: While loops 

*If you are working in CodeSpaces work in file **`4b_part1.py`***

The following code uses a `for` loop to generate 15 values in a sequence. 

Try the code out to see its output.

```python
x = 2
for i in range(15):
    print(x)
    x = x*2
```

Rewrite the code using a while loop to generate the sequence terms, but that will stop looping once `x` is greater or equal to 2000.

(i.e. so the last value printed is the last one in the sequence that is below 2000).

The condition should work to stop the loop whatever value of `x` is set on the first line. 

(If you try different values remember to change it back to `2` before submission).

---

### Part 2: If statements  

A company are writing software to run a bike hire company.

The software stores information on the customer in three variables as shown below:

```python
fullname = "A N Other"
age = 23
height_cm = 155
```

**2. i** 

*If you are working in CodeSpaces work in file **`4b_part2_i.py`***

To rent a bike customers have to be 18 or over.

Start your file by copying in the code section that sets up the three customer variables.

Write code that displays the message: 

```
checking age
```

Then write an `if` statement that displays a message based on their stored age.

This should display:

 - `deny rental` if the customer is under 18
 - `approve rental` if the customer is 18 or over

Test your code with different values, but set the age back to `23` before submission.

---

**2. ii**

*If you are working in CodeSpaces work in file **`4b_part2_ii.py`***

The bike rental company have three sizes of bike they hire out to customers

**`S`** for customers smaller than 140cm
**`M`** for customers between 140cm and 160cm inclusive
**`L`** for customers larger than 160cm

Start your file by copying in the code section that sets up the three customer variables.

Write code that displays the message: 

```
finding size
```

Then write an `if`-`elif`-`else` block that displays the appropriate message from the below according to the stored height.

 - **`rent S bike`** 
 - **`rent M bike`**
 - **`rent L bike`**

Test your code with different values, but set the height back to `155` before submission.

---

### Part 3: Dictionaries

**3. i**

*If you are working in CodeSpaces work in file **`4b_part3_i.py`***

Start with the following lines of code:

```python
customer_data = []
```

Now add code lines to:

 - create an empty Python dictionary called: `customer`
 - store the following customer data into the dictionary:
 
   key `fullname`, value `B Wiggins`
   key `age`, value `45`
   key `height_cm`, value `190`

 - add the dictionary you created into the `customer_data` list
 - print the list to screen

---

**3. ii**

*If you are working in CodeSpaces work in file **`4b_part3_ii.py`***

The bike rental company store the level of stock in a python dictionary like the one below:

```python
stock_levels = { "S": 10, "M": 23, "L": 17 }
```

a) Starting with this line that defines the dictionary, write Python code that loops over the entries to produce a stock report in the following format:

```
number of bikes in stock
S 10
M 23
L 17
```

b) Edit your code so that it can also add the number of each type of the three bikes and display a final line:

```
total 50
```

---

### Submitting your work

Run the following lines in the terminal to stage, commit and push your code back to your GitHub repository:

```
git add .
git commit -m "completed 4b"
git push
```

To check your work has been saved you can run the line of code below in the terminal to get the web address of the repository in GitHub. Goto the repository and check the completed code files are stored.

```
git config --get remote.origin.url
```
