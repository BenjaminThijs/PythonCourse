# Introduction

To make a python script, you need to simply create a file with the `.py` extension. \
This script can then be edited using any text editor. \
To run the file, as seen before we call `python <script>.py`. \
\
The script file can be created anywhere, for this course we will create a new repository on github. \
This repository will contain all the exercises per lesson.


## Creating a repo on github

First of all, you need an account on github, but since this course is posted on github, I will assume you already have this. \
Next, you need to create a new repo on github. \

 - TODO: explain how to do this?

Clone this new repository to your computer. \
Per lesson you will create a new folder, by the same name as the lesson you are currently taking. (`Lesson01` in this case) \
This folder will then contain a folder for each exercise in this lesson. (`Exercise 1` for example) \
These exercise folders will then contain the actual exercises. \
\
Exercises will be listed on the bottom of each README file per lesson. \
Any other examples given will also be included in the repo, this includes scripts shown through screenshots.

## Printing messages

In [Lesson00](../Lesson00/) we ran a script called `main.py`, this script showed a message to the user. \
Now we will learn how to do this ourselves. \
\
If you were to open up the [script from last lesson](../Lesson00/main.py), you can see what the code looks like. \
![alt text](Resources/Lesson00Script.png "Lesson00 main script")
\
As you can see, it is only one line of code. \
A `print` is called, this `print` name is what is called a `method`. \
For now, it is not yet important what the word `method` means. \
All you need to know is that calling `print` with parentheses (brackets -> `(` and `)`) will allow you to show messages on the screen. \
\
What exactly you will display depends on what you put between the parentheses. \
As seen in the [script from last lesson](../Lesson00/main.py) some text was shown. \
Text in most programming languages, including Python, is encased in quotation marks (`"`). \
So in order to print another message, all you would need to do is change what is between those quotation marks. \
**Example** \
![alt text](Resources/PrintExample.png "Print example")
\
We can also add multiple print statements in a row. \
**Code** \
![alt text](Resources/MultiplePrints.png "Printing multiple times") \
**Output** \
![alt text](Resources/MultiplePrintsOutput.png "Output from printing multiple times")
\
A few new things got introduced here. \
The `print` statement not only shows a message to the user, but also makes sure the next output is shown a line lower. \
This causes the second print message to show it's message on the line below the first one. \
\
Another new thing is an empty `print` statement (line 3). \
If `print` is called without anything to print, it will print an empty line. \
\
A third thing is comments, comments are text that the programmer can see, but the program ignores them. \
A comment in Python looks like this:
```python
# Comment
```
Anything written after the `#` symbol will be treated as simply text by your computer, and will thus do nothing in your program. \
This is a good way to write down what a piece of code does, so you or anyone else can know without having to read the actual code.

## Variables

A variable is a way of saving a value. \
This sounds quite abstract but will become clearer soon. \
A variable can contain a large amount of different values, for now we will take a look at some of the more basic ones.

### Strings

We have already seen `strings` even though they were never named as such. \
A `string` looks like this:
```python
"Some text"
```
\
A `string` can contain different character, usually: letters, numbers, spaces, ... \
\
A `string` is not a variable, it is a value. \
A variable is some name which is linked to a certain value. \
**Code**
```python
some_string = "Some text"
```
\
As seen before, we can display a string using the `print` statement. \
Up until now we have only seen `print` get called using a value (a string), but it can also be used with a variable. \

**Code**
```python
print(some_string)
```
\
All of this put together gives us (see [the example](PrintString.py))
```python
some_string = "Some text"

print(some_string)
```
\
Something to note here is the empty line of code, which is simply there to make our code more readable. \
An empty line of code will just get skipped by your computer when running the code.

## Exercises
### Exercise 1

Create a Python script called `Exercise1.py` and open it. \

