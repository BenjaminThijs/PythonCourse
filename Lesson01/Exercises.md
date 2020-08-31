# Exercises

In each lesson, a folder has been created for you to put your answers (nobody but you will be able to see them, they will not become part of this course's repository). \
Each seperate exercise also contains a folder to put the answer in. \
It is not required to use these folders, but it is encouraged, since at later points these folders might contain some starting code. \
\
Each exercise also has a difficulty level, shown using stars. More stars equals more difficult. (difficulty is based on the lesson, not an overall score)

## Exercise 1 *

Create a new python script (you can choose the name). \
Paste this code inside and run the code. \
```python
print("You made your very first script!!!")
```

<details><summary><b>Hint</b></summary>

Make sure you are in the correct directory. \
This means, you need to be in the directory `Lesson01/Exercises/Exercise 1` inside the repo. \
Use `cd <directory>` to move to a directory. \
You can sue `cd ..` to go one directory up.

</details>

<details><summary><b>Answer</b></summary>

Make sure you are in the correct directory (see hint). \
Run `python <your script name>.py`.

</details>

## Exercise 2 **

Create a python script. \
Inside the script, create a variable which contains a name. \
Then show the name to the user. 

<details><summary><b>Hint</b></summary>

A name is a string.

</details>

<details><summary><b>Answer</b></summary>

```python
name = "John F. Kennedy"

print(name)
```

</details>

### Exercise 3 ***

Create a python script. \
Create a variable containing the amount of doors in your house (do this from memory, so don't go count them yet, guess if needed). \
Create another variable which containd the actual amount of doors in your house (meaning, you now need to go count them). \
\
Calculate the difference between your estimation and the actual number of doors and put this value in a variable. \
Then show this difference. \
\
**ps.** \
The order does not matter for this exercise.

<details><summary><b>Hint</b></summary>

Use the `-` operator.

</details>

<details><summary><b>Answer</b></summary>

Exact naming of variables does not matter. \
The answers shown will by no means be the only possible answer. \
\
```python
estimation = 12
actual = 16

difference = estimation - actual

# Since order is not important the following would also be fine for this exercise
# difference = actual - estimation

print(difference)
```

</details>

## Exercise 4 ****

The folder for exercise 4 already contains a script. \
This script contains 4 values, all numbers. \
\
Show the difference between the first number and the second number. \
Show the sum of the second and fourth number. \
Show the product of the third and fourth number. (product = `something` times `something else`) \
Show the quotient of the first and third number. (quotient = `something` divided by `something else`) \
\
Lastly make a new variable called `value`, this variable will contain:
 - the first number
 - times the third number
 - minus the fourth number
 - divided by the fifth number
\
Show this variable too. \
\
Run the script.

<details><summary><b>Hint</b></summary>

For the first four things, there is no need to make new variables, but you can do so if you want to. \
\
For the last variable, make sure your order of operations are correct. \
You can achieve this by using extra brackets if needed.

</details>

<details><summary><b>Answer</b></summary>

```python
first_number = 15
second_number = -11
third_number = 2
fourth_number = 5.2

print(first_number - second_number)
print(second_number + fourth_number)
print(third_number * fourth_number)
print(first_number / third_number)

value = (first_number * third_number - fourth_number) / fifth_number

print(value)
```

</details>

## Exercise 5 *****

Create a script. \
\
In this script create some variables for:
 - your name
 - your age
 - your favorite hobby
 - your lifegoal (just one is fine)
 - your favorite color
 - your favorite food
\
Now show all of this information using 1 print statement, preferably using string formatting. \
Try to make everything readable though, so print more than one line. (but still using 1 print statement) \
Exactly how you choose to phrase everything does not matter, the important thing is only using 1 print statement. (this can be done in multiple ways) \
\
An example of what some output might look like is this. \
```
My name is Bert and I am 18 years old.
I like fishing and would like to become the best fisher of all time.
I really like the color purple and go crazy for kitkat bars.
```

<details><summary><b>Hint</b></summary>

Showing things on multiple lines made use of the `\n` character. \
\
To only use 1 print statement, you can put your output into a new variable, and print that. \
Or you can create the string and print it directly. \
\
String formatting needs your string to look like this `f"blabla {something} blabla"`.

</details>

<details><summary><b>Answer</b></summary>

```python
name = "Bert"
age = 18
hobby = "fishing"
lifegoal = "to become the best fisher of all time"
favorite_color = "purple"
favorite_food = "kitkat bars"

print(f"My name is {name} and I am {age} years old.\nI like {hobby} and would like {lifegoal}.\nI really like the color {favorite_color} and go crazy for {favorite_food}.")
```

</details>
\
\
[Next lesson](../Lesson02)