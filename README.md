# "Build in Public" in BrainF

[Run this project](https://www.google.com/search?q=BrainF%20compiler): Copy and paste this in one of the BrainF compilers.

This is a code showing how to print "Build in Public" in an esoteric programming language called BrainF**k.

Comments are shown to tell steps of initiating and printing every single letter step by step.

BrainF consists of boxes (or bytes) which are increased and decreased to have an ASCII value for the particular letter you want to execute.

This code first starts with putting the value of the box at 0 level (first box) as 10.

Then a loop is executed which adds 6 in box 1, 11 in box 2, 8 in box 3, 3 in box 4, and decreases 1 in box 0, everytime it runs.

As the bytes can't go negative, the loop breaks when the value of box 0 becomes zero, which makes the loop run 10 times, and gives us:

- Box 1 = 60
- Box 2 = 110
- Box 3 = 80
- Box 4 = 30

After that, it tries to manipulate these boxes to get the desired ASCII values for the respective letters to print.

ASCII table for letters to print:
- B = 66
- u = 117
- i = 105
- l = 108
- d = 100
- (space) = 32
- i = 105
- n = 110
- (space) = 32
- P = 80
- u = 117
- b = 98
- l = 108
- i = 105
- c = 99

# Links
<h3>Made by Tejas</h3>
<a href="x.com/tejasm_" target="_blank">X</a><br/>
<a href="github.com/tejasm-dev" target="_blank">GitHub</a>