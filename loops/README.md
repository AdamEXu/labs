# Loops

If you ever played Super Mario Bros. back in the day, you might recall this scene, wherein four question marks were hovering in the sky:

![four question marks in a row](mario.png)

Let's recreate a bit of that game, albeit in text!

In `mario.py` in the text editor at top-right, implement a program that prints, quite simply, `????`, followed by a newline (`\n`), without using a loop.

{% next %}

Elsewhere in Super Mario Bros., there might be more (or even fewer) than four question marks in the sky. Let's prepare for as much.

Modify `mario.py` in the text editor at top-right in such a way that the program prints, quite simply, `????`, again followed by a newline, this time using a loop to print each question mark one at a time, each on the same line.

{% spoiler "Hints" %}

To print a question mark without a newline (i.e., line break) after it, you can use

```
print("?", end="")
```

which appends `""` (i.e., the "empty string") to each question mark instead of, `"\n"` (which represents a newline), the default.

Indeed,

```
print("?")
```

is actually equivalent to

```
print("?", end="\n")
```

but is quicker to type!

To print only a newline, meanwhile, you can use

```
print()
```

without any arguments!

{% endspoiler %}

{% next %}

Okay, your program still only prints four question marks, and somehow we've gone and made it more complicated nonetheless. But consider that just a step toward this final goal! (Boss level!)

Modify `mario.py` in the text editor at top-right in such a way that the program

1. prompts the user for a positive integer, and
1. prints that many question marks, all on the same line, followed by a newline.

{% next %}

To submit your work, execute the below.

```
submit50 cs50/labs/cscip14300/loops
```
