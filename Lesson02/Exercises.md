# Exercises

In each lesson, a folder has been created for you to put your answers (nobody but you will be able to see them, they will not become part of this course's repository). \
Each seperate exercise also contains a folder to put the answer in. \
It is not required to use these folders, but it is encouraged, since at later points these folders might contain some starting code. \
\
Each exercise also has a difficulty level, shown using stars. More stars equals more difficult. (difficulty is based on the lesson, not an overall score)

## Exercise 1 *

In the `main.py` script, ask the user for their name and their age. \
Show both of these to the user in one message. \
\
Example output: `You are Ernie and are 16 years old.` \
Try to use string formatting.

<details><summary><b>Hint</b></summary>

Use the `input` statement. \
For the age you will may want to cast to an `int`, although it is not required here. \
\
String formatting was done using `f"{variable}"`

</details>

<details><summary><b>Answer</b></summary>

```python
name = input("Please enter your name: ")
age = int(input("Please enter your age: "))

print(f"You are {name} and are {age} years old")
```

</details>

## Exercise 2 **

A script has been provided for you to program in. \
Ask the user for his name, if his name is Jack tell him "You are ugly". \
If it is not Jack, tell him "Jack is ugly".

<details><summary><b>Hint</b></summary>

Use the `==` operator to check for equality. \
You are going to need an `if-else`-statement.

</details>

<details><summary><b>Answer</b></summary>

```python
name = input("Please enter your name: ")

if name == "Jack":
    print("You are ugly")
else:
    print("Jack is ugly")
```

</details>

## Exercise 3 ***

Ask the name and age of the user. \
\
If the user is not Jack, and they are older than 40 (Jack's age), tell them they are older than Jack. \
If it is Jack, tell him he is still ugly.

<details><summary><b>Hint</b></summary>

Use the `!=` operator to check for inequality. \
You are going to need two `if`-statements, aswell as the `and` operator.

</details>

<details><summary><b>Answer</b></summary>

```python
name = input("Please enter your name: ")
age = int(input("Please enter your age: "))

if name != "Jack" and age > 40:
    print("You are older than Jack")

if name == "Jack":
    print("You are still ugly")
```

</details>

## Exercise 4 *****

Ask the user for their age and that of their father. \
\
Show the user how much older their father is than them. \
Also show how old they are combined. \
\
Next show the user if they are an adult (18+), a teenager (13+), a child (3+), or a toddler. 

<details><summary><b>Hint</b></summary>

Use the `int` keyword to cast to an integer. \
Use the `-` operator to calculate a difference. \
Use the `+` operator to calculate a sum. \
\
You are going to need an `if-elif-else`-statement.

</details>

<details><summary><b>Answer</b></summary>

```python
age = int(input("Please enter your age: "))
father_age = int(input("Please enter your father's age: "))

age_difference = father_age - age
print(f"The difference between your ages is {age_difference} years.")

age_sum = father_age + age
print(f"Together you are {age_sum} years old.")

if age >= 18:
    print("You are an adult")
elif age >= 13:
    print("You are a teenager")
elif age >= 3:
    print("You are a child")
else:
    print("You are a toddler")
```

</details>