# x86-64-assembly-macos-hello-world
A "Hello, World!" example in x86-64 assembly for macOS
<br/><br/>

### Follow along the full tutorial: <a href="https://zerodayarcade.com/tutorials/hello-world-assembly-macos">Learn x86-64 Assembly for macOS: Hello World</a>

The full tutorial includes complete instructions and a line-by-line code explanation.
<br/><br/>


## Get the code
Clone this project:
```
git clone https://github.com/ZeroDayArcade/x86-64-assembly-macos-hello-world.git
```
cd into the project directory:
```
cd x86-64-assembly-macos-hello-world
```

## Assemble the program
Assemble the code into an object (.o) file:
```
as hello_assembly.s -o hello_assembly.o
```
Create a UNIX executable with the object file using gcc:
```
gcc -o hello_assembly hello_assembly.o -nostdlib -static
```

## Run the program
```
./hello_assembly
```
You should now see "Hello, World!" printed in the Terminal.

<br/>

# More Zero Day Arcade Tutorials:
<a href="https://zerodayarcade.com/tutorials">zerodayarcade.com/tutorials</a>

# Find Hacking Bounties in Gaming:
<a href="https://zerodayarcade.com/bounties">zerodayarcade.com/bounties</a>
