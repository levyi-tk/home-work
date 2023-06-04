# Indoor Voice

WRITING IN ALL CAPS IS LIKE YELLING.

Best to use your “indoor voice” sometimes, writing entirely in lowercase.

In a file called indoor.py, implement a program in Python that prompts the user for input
 and then outputs that same input in lowercase. Punctuation and whitespace should be outputted unchanged.
 You’re welcome, but not required, to prompt the user explicitly,
 as by passing a str of your own as an argument to input.

<details>
<summary>Hints</summary>
<br>

- Recall that input returns a str, per <a href="https://docs.python.org/3/library/functions.html#input">docs.python.org/3/library/functions.html#input</a>
- Recall that a str comes with quite a few methods, per <a href="https://docs.python.org/3/library/stdtypes.html#string-methods">docs.python.org/3/library/stdtypes.html#string-methods</a>
</details>

<br>

# Before You Begin
Execute cd by itself in your terminal window. You should find that your terminal window’s prompt resembles the below:

```
$
```
Next execute

```
mkdir indoor
```
to make a folder called indoor in your codespace.

Then execute

```
cd indoor
```
to change directories into that folder. You should now see your terminal prompt as `indoor/ $`. You can now execute

```
code indoor.py
```
to make a file called indoor.py where you’ll write your program.

<br />

# Demo

[![asciicast](https://asciinema.org/a/oJYP3MGpxunrgkONnDLl4xKAj.svg)](https://asciinema.org/a/oJYP3MGpxunrgkONnDLl4xKAj)

<!-- <script async id="asciicast-oJYP3MGpxunrgkONnDLl4xKAj" src="https://asciinema.org/a/oJYP3MGpxunrgkONnDLl4xKAj.js"></script> -->

<br />

# How to Test
Here’s how to test your code manually. At the `indoor/ $` prompt in your terminal: :

- Run your program with `python indoor.py`. Type `HELLO` and press Enter. Your program should output `hello`.
  
- Run your program with `python indoor.py`. Type `THIS IS BLUE-TECH` and press Enter. Your program should output `this is blue-tech`.
- Run your program with `python indoor.py`. Type `50` and press Enter. Your program should output `50`.
  
If you run into an error saying your file cannot be opened, retrace your steps to be sure that you are inside your `indoor` folder and have saved your `indoor.py` file there. Remember how?

