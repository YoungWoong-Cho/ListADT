# ListADT
This is a program that manipulates stacks and queues. The program asks the user for the name of an input text file and an output text file, and executes the command in the input text file to create stacks/queues, push/pop values, and print out error messages for invalid commands.

Following are sample input and output text files.

Input.txt
create i1 queue
create i1 queue
create i1 stack
create i2 stack
create s99 stack
push i1 50
push i1 100
push i2 -50
push i2 100
push s99 Hello
push s99 World
pop i2
pop s99
push s99 planet
pop i2
push i2 150
pop s99
pop s99
create d99 stack
push d99 0.123
push d99 -0.456
pop d99
pop s99
push dHelloWorld 0.5
pop dHelloWorld
push i2 200
pop i2
pop i1
push i1 150
push i1 200
pop i1
create dHelloWorld stack
create dHelloPlanet queue
push dHelloWorld 3.14
pop i2
pop i2
push dHelloWorld 3.1415
push dHelloPlanet -60.5
push dHelloWorld -1
pop dHelloWorld
pop dHelloPlanet
pop sR2D2
create sR2D2 queue
pop sR2D2
push sR2D2 123abcDEF
push sR2D2 G4H5I6j7k8l9
pop sR2D2
pop sR2D2
pop sR2D2
pop dHelloWorld
pop dHelloWorld
pop dHelloWorld

Output.txt
PROCESSING COMMAND: create i1 queue
PROCESSING COMMAND: create i1 queue
ERROR: This name already exists!
PROCESSING COMMAND: create i1 stack
ERROR: This name already exists!
PROCESSING COMMAND: create i2 stack
PROCESSING COMMAND: create s99 stack
PROCESSING COMMAND: push i1 50
PROCESSING COMMAND: push i1 100
PROCESSING COMMAND: push i2 -50
PROCESSING COMMAND: push i2 100
PROCESSING COMMAND: push s99 Hello
PROCESSING COMMAND: push s99 World
PROCESSING COMMAND: pop i2
Value popped: 100
PROCESSING COMMAND: pop s99
Value popped: World
PROCESSING COMMAND: push s99 planet
PROCESSING COMMAND: pop i2
Value popped: -50
PROCESSING COMMAND: push i2 150
PROCESSING COMMAND: pop s99
Value popped: planet
PROCESSING COMMAND: pop s99
Value popped: Hello
PROCESSING COMMAND: create d99 stack
PROCESSING COMMAND: push d99 0.123
PROCESSING COMMAND: push d99 -0.456
PROCESSING COMMAND: pop d99
Value popped: -0.456
PROCESSING COMMAND: pop s99
ERROR: This list is empty!
PROCESSING COMMAND: push dHelloWorld 0.5
ERROR: This name does not exist!
PROCESSING COMMAND: pop dHelloWorld
ERROR: This name does not exist!
PROCESSING COMMAND: push i2 200
PROCESSING COMMAND: pop i2
Value popped: 200
PROCESSING COMMAND: pop i1
Value popped: 50
PROCESSING COMMAND: push i1 150
PROCESSING COMMAND: push i1 200
PROCESSING COMMAND: pop i1
Value popped: 100
PROCESSING COMMAND: create dHelloWorld stack
PROCESSING COMMAND: create dHelloPlanet queue
PROCESSING COMMAND: push dHelloWorld 3.14
PROCESSING COMMAND: pop i2
Value popped: 150
PROCESSING COMMAND: pop i2
ERROR: This list is empty!
PROCESSING COMMAND: push dHelloWorld 3.1415
PROCESSING COMMAND: push dHelloPlanet -60.5
PROCESSING COMMAND: push dHelloWorld -1
PROCESSING COMMAND: pop dHelloWorld
Value popped: -1
PROCESSING COMMAND: pop dHelloPlanet
Value popped: -60.5
PROCESSING COMMAND: pop sR2D2
ERROR: This name does not exist!
PROCESSING COMMAND: create sR2D2 queue
PROCESSING COMMAND: pop sR2D2
ERROR: This list is empty!
PROCESSING COMMAND: push sR2D2 123abcDEF
PROCESSING COMMAND: push sR2D2 G4H5I6j7k8l9
PROCESSING COMMAND: pop sR2D2
Value popped: 123abcDEF
PROCESSING COMMAND: pop sR2D2
Value popped: G4H5I6j7k8l9
PROCESSING COMMAND: pop sR2D2
ERROR: This list is empty!
PROCESSING COMMAND: pop dHelloWorld
Value popped: 3.1415
PROCESSING COMMAND: pop dHelloWorld
Value popped: 3.14
PROCESSING COMMAND: pop dHelloWorld
ERROR: This list is empty!
