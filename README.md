# POSIX shell ANSI exploration

I used this amazing person's work to write this program:

[Zhee](https://gist.github.com/zchee/ea41b5c598b43006d029c8990377aa90)

This program, which I aptly named `ansi`, showcases changing colors,
ringing the bell, hiding the user's input, blinking text, and
removing the effects of these escape characters.

Amazing, world-changing, and other superlatives, I know.  You can
use this program to test how your 16 basic colors will look on your
terminal, and also as a reference/cheatsheet.

This program takes no arguments. Further instructions will be
shown upon running the program.

If you're new to programming, you can download this code like
so (from your terminal):

```
# Download this code from git
git clone https://github.com/ferzeg3420/ANSI-exploration.git

# Make the code executable (dangerous for code you don't what it
# does)
chmod +x

# Run the program
ansi ./ansi 
```

- Each line is a command, but if it starts with #, it's a comment.

- If you would like to keep this code as a normal command, you can
then move `ansi`, the file, to a directory listed in your `$PATH`
variable. An appropriate one would be `~/bin`, so `mv ansi ~/bin`.
After doing that, you should be able to do `ansi` from any 
directory in your terminal.

- Word of advice: Don't download random programs from the
internet if you don't know what they do. In this case it
is okay (but you should still read through the code here
and understand what's going on fully).
