# Tip Calculator
>And now for my Wizard tip calculator.
>
>— Morty Seinfeld
>

In the United States, it’s customary to leave a tip for your server after dining in a restaurant, typically an amount equal to 15% or more of your meal’s cost. Not to worry, though, we’ve written a tip calculator for you, below!

```py
def main():
    dollars = dollars_to_float(input("How much was the meal? "))
    percent = percent_to_float(input("What percentage would you like to tip? "))
    tip = dollars * percent
    print(f"Leave ${tip:.2f}")


def dollars_to_float(d):
    # TODO


def percent_to_float(p):
    # TODO


main()
```
Well, we’ve written most of a tip calculator for you. Unfortunately, we didn’t have time to implement two functions:

- `dollars_to_float`, which should accept a `str` as input (formatted as `$##.##`, wherein each `#` is a decimal digit), remove the leading `$`, and return the amount as a `float`. For instance, given `$50.00` as input, it should return `50.0`.
- `percent_to_float`, which should accept a `str` as input (formatted as `##%`, wherein each `#` is a decimal digit), remove the trailing `%`, and return the percentage as a `float`. For instance, given `15%` as input, it should return `0.15`.


Assume that the user will input values in the expected formats.

<details>
<summary>Hints</summary>
<br>

- Recall that input returns a str, per <a href="https://docs.python.org/3/library/functions.html#input">docs.python.org/3/library/functions.html#input</a>
- Recall that float can convert a str to a float, per <a href="https://docs.python.org/3/library/functions.html#float"> docs.python.org/3/library/functions.html#float.</a>
- Recall that a str comes with quite a few methods, per <a href="https://docs.python.org/3/library/stdtypes.html#string-methods">docs.python.org/3/library/stdtypes.html#string-methods</a>
</details>

<br>



# Demo
[![asciicast](https://asciinema.org/a/lv5OXINayVRvV5LtPQ528MTNi.svg)](https://asciinema.org/a/lv5OXINayVRvV5LtPQ528MTNi)


# Before You Begin
execute `cd` by itself. You should find that your terminal window’s prompt resembles the below:
```
$
```
Next execute

```
mkdir tip
```
to make a folder called `tip` in your codespace.

Then execute

```
cd tip
```
to change directories into that folder. You should now see your terminal prompt as `tip/ $`. You can now execute

```
code tip.py
```
to make a file called `tip.py`. Copy and paste the code above into a file, and complete the implementations of  `dollars_to_float` and `percent_to_float`, replacing each `TODO` with one or more lines of your own code.

# How to Test
Here’s how to test your code manually:

Run your program with `python tip.py`. Type `$50.00` and press Enter. Then, type `15%`and press Enter. Your program should output:

```
Leave $7.50    
```
Run your program with `python tip.py`. Type `$100.00` and press Enter. Then, type `18%` and press Enter. Your program should output:
```
Leave $18.00
```
Run your program with `python tip.py`. Type `$15.00` and press Enter. Then, type `25%` and press Enter. Your program should output
```
Leave $3.75
```
