# Branching and Iteration
## Q1: 
What is wrong with the example below?
```
a = 3
b = 20
if b > a:
print("b is greater than a")
```

This is ok but less readable: 
```
if b > a: print("b is greater than a")
```

## Q2: 
Write a coditional statement for every possible case comparing two numbers. Try to use both `elif` and `else`.

There is a short statement for `if...else` as well but again, less readable:

```
print("a is greater") if a > b else print("b is greater or equal")
```

## Q3:
Use logical `and, or` statements to compare a number `a` to other two numbers `b` and `c`. We are especially interested in these two cases:
* if it is greater than both or
* if it is greater than at least one of them.

## Q4:
Use nested `if...else` statement to write every possible case for comparing three numbers. **Hint: ** There are 9 total cases

## Q5:
Can a `if` statement be empty? In other words, will the code below give an error if you leave it like that?

```
if a > b:
```
# For Loops

## Q6:

Write a `for` loop that prints even numbers up to 100.

**Hints**:
* There are multiple ways of doing that. For example, you could check every number from 1 to 100 and print if it is divisible by 2. Or, you could do it with a counter which is initialized to 1 and incremented by 2 at each iteration.

## Q7:
Write a `for` loop that prints each character of the string `"Coding_is_fun!"`

## Q8:
Repeat Q7, but print a space `" "` instead of `"_"`.

**Hint**: Use an `if` statement inside the `for` loop

## Q9:
Suppose you have 2 strings:
```
str1 = "abc"
str2 = "12"
```
Print the concatanetation of each charachter in `str1` with each charachter in `str2`, for example for the given input, you should print:
```
a1
b1
c1
a2
b2
c2
```
**Hint**: Use nested `for` loops

# While Loops

## Q10:

Write a `while` loop that prints odd numbers up to 100.

**Hints**:
* There are multiple ways of doing that. For example, you could check every number from 1 to 100 and print if it is divisible by 2. Or, you could do it with a counter which is initialized to 1 and incremented by 2 at each iteration.


## Q11:
Write a `while` loop that prints the characters in a string until an exclamation mark `!`. For example, for the following input

`"Coding is fun! For now."` 

It should print:

`"Coding is fun!"`

**Hints**: 
* Initialize a boolean variable as `True` before the loop. You will use this as your `while` loop condition. Change your boolean variable to `False` when you detect a `"!"` character in your `while` loop. As long as this variable is `True`, you print the character.
* You can access each character in your string using an integer `i`. For example, let `str = "Coding is fun! For now."`. If `i = 0`, then `str[i]` is the character `C`. If `i = 1`, then `str[i]` is the character `o`.

```
no_exclamation = True
str = "Coding is fun! For now."
i = 0
while no_exclamation:
  char = str[i]

  #  To-Do:
  #  print char
  #  increment i
  #  check if char equals "!", and update no_exclamation
```

## Q12
Repeat Q11. But this time, DO NOT use a boolean variable. 

**Hint**: use `break`
