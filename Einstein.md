# Einstein
Even if you haven’t studied physics (recently or ever!), you might have heard that \(E = mc^2\), wherein \(E\) represents energy (measured in Joules), \(m\) represents mass (measured in kilograms), and \(c\) represents the speed of light (measured approximately as 300000000 meters per second), per Albert Einstein et al. Essentially, the formula means that mass and energy are equivalent.

In a file called `einstein.py`, implement a program in Python that prompts the user for mass as an integer (in kilograms) and then outputs the equivalent number of Joules as an integer. Assume that the user will input an integer.

<details>
<summary>Hints</summary>
<br>

- Recall that input returns a str, per <a href="https://docs.python.org/3/library/functions.html#input">docs.python.org/3/library/functions.html#input</a>
- Recall that int can convert a str to an int, per . <a href="https://docs.python.org/3/library/functions.html#int">docs.python.org/3/library/functions.html#int</a>
- Recall that Python comes with several built-in functions, per <a href="https://docs.python.org/3/library/functions.html">docs.python.org/3/library/functions.html</a>
</details>

<br>

# Demo
[![asciicast](https://asciinema.org/a/c8LucTNvoRMLZU1RAKAwWyTSX.svg)](https://asciinema.org/a/c8LucTNvoRMLZU1RAKAwWyTSX)

# Before You Begin
prompt resembles the below:

```
$
```
Next execute

```
mkdir einstein
```
to make a folder called `einstein` in your codespace.

Then execute

```
cd einstein
```
to change directories into that folder. You should now see your terminal prompt as `einstein/ $`. You can now execute

```
code einstein.py
```
to make a file called `einstein.py` where you’ll write your program.

# How to Test
Here’s how to test your code manually:

Run your program with `python einstein.py`. Type `1` and press Enter. Your program should output:
```
90000000000000000
```
Run your program with `python einstein.py`. Type `14` and press Enter. Your program should output:
```
1260000000000000000
```
Run your program with `python einstein.py`. Type `50` and press Enter. Your program should output
```
4500000000000000000
```
