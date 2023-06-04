# Playback Speed
Some people have a habit of ~~lecturing~~ speaking rather quickly, and it’d be nice to slow them down, a la YouTube’s 0.75 playback speed, or even by having them pause between words.

In a file called `playback.py`, implement a program in Python that prompts the user for input and then outputs that same input, replacing each space with `...` (i.e., three periods).

<details>
<summary>Hints</summary>
<br>

- Recall that input returns a str, per <a href='https://docs.python.org/3/library/functions.html#input'>docs.python.org/3/library/functions.html#input.</a>
- Recall that a str comes with quite a few methods, per <a href='https://docs.python.org/3/library/stdtypes.html#string-methods'>docs.python.org/3/library/stdtypes.html#string-methods.</a>
</details>
<br>



# Demo

[![asciicast](https://asciinema.org/a/UmJeo6gLJxqDh0uW0gJaTG9JE.svg)](https://asciinema.org/a/UmJeo6gLJxqDh0uW0gJaTG9JE)

# Before You Begin
 You should find that your terminal window’s prompt resembles the below:

```
$
```
Next execute

```
mkdir playback
```
to make a folder called playback in your codespace.

Then execute

```
cd playback
```
to change directories into that folder. You should now see your terminal prompt as `playback/ $`. You can now execute

```
code playback.py
```
to make a file called playback.py where you’ll write your program.

<br >

# How to Test
Here’s how to test your code manually:

Run your program with 
```
python playback.py
```
Type `This is CS101` and press Enter. Your program should output:
```
This...is...CS101
```    
Run your program with `python playback.py`. Type `This is our week on functions` and press Enter. Your program should output:
```
This...is...our...week...on...functions
```
Run your program with python playback.py. Type `Let's implement a function called hello` and press Enter. Your program should output
```
Let's...implement...a...function...called...hello
```