# StackQueue
This is a program that manipulates stacks and queues. The program asks the user for the name of an input text file and an output text file, and executes the command in the input text file to create stacks/queues, push/pop values, and print out error messages for invalid commands.

Following are sample input and output text files.

<Strong>input.txt</Strong><br>
create i1 queue<br>
create i1 queue<br>
create i1 stack<br>
create i2 stack<br>
create s99 stack<br>
push i1 50<br>
push i1 100<br>
push i2 -50<br>
push i2 100<br>
push s99 Hello<br>
push s99 World<br>
pop i2<br>
pop s99<br>
push s99 planet<br>
pop i2<br>
push i2 150<br>
pop s99<br>
pop s99<br>
create d99 stack<br>
push d99 0.123<br>
push d99 -0.456<br>
pop d99<br>
pop s99<br>
push dHelloWorld 0.5<br>
pop dHelloWorld<br>
push i2 200<br>
pop i2<br>
pop i1<br>
push i1 150<br>
push i1 200<br>
pop i1<br>
create dHelloWorld stack<br>
create dHelloPlanet queue<br>
push dHelloWorld 3.14<br>
pop i2<br>
pop i2<br>
push dHelloWorld 3.1415<br>
push dHelloPlanet -60.5<br>
push dHelloWorld -1<br>
pop dHelloWorld<br>
pop dHelloPlanet<br>
pop sR2D2<br>
create sR2D2 queue<br>
pop sR2D2<br>
push sR2D2 123abcDEF<br>
push sR2D2 G4H5I6j7k8l9<br>
pop sR2D2<br>
pop sR2D2<br>
pop sR2D2<br>
pop dHelloWorld<br>
pop dHelloWorld<br>
pop dHelloWorld<br>

<strong>output.txt</strong><br>
PROCESSING COMMAND: create i1 queue<br>
PROCESSING COMMAND: create i1 queue<br>
ERROR: This name already exists!<br>
PROCESSING COMMAND: create i1 stack<br>
ERROR: This name already exists!<br>
PROCESSING COMMAND: create i2 stack<br>
PROCESSING COMMAND: create s99 stack<br>
PROCESSING COMMAND: push i1 50<br>
PROCESSING COMMAND: push i1 100<br>
PROCESSING COMMAND: push i2 -50<br>
PROCESSING COMMAND: push i2 100<br>
PROCESSING COMMAND: push s99 Hello<br>
PROCESSING COMMAND: push s99 World<br>
PROCESSING COMMAND: pop i2<br>
Value popped: 100<br>
PROCESSING COMMAND: pop s99<br>
Value popped: World<br>
PROCESSING COMMAND: push s99 planet<br>
PROCESSING COMMAND: pop i2<br>
Value popped: -50<br>
PROCESSING COMMAND: push i2 150<br>
PROCESSING COMMAND: pop s99<br>
Value popped: planet<br>
PROCESSING COMMAND: pop s99<br>
Value popped: Hello<br>
PROCESSING COMMAND: create d99 stack<br>
PROCESSING COMMAND: push d99 0.123<br>
PROCESSING COMMAND: push d99 -0.456<br>
PROCESSING COMMAND: pop d99<br>
Value popped: -0.456<br>
PROCESSING COMMAND: pop s99<br>
ERROR: This list is empty!<br>
PROCESSING COMMAND: push dHelloWorld 0.5<br>
ERROR: This name does not exist!<br>
PROCESSING COMMAND: pop dHelloWorld<br>
ERROR: This name does not exist!<br>
PROCESSING COMMAND: push i2 200<br>
PROCESSING COMMAND: pop i2<br>
Value popped: 200<br>
PROCESSING COMMAND: pop i1<br>
Value popped: 50<br>
PROCESSING COMMAND: push i1 150<br>
PROCESSING COMMAND: push i1 200<br>
PROCESSING COMMAND: pop i1<br>
Value popped: 100<br>
PROCESSING COMMAND: create dHelloWorld stack<br>
PROCESSING COMMAND: create dHelloPlanet queue<br>
PROCESSING COMMAND: push dHelloWorld 3.14<br>
PROCESSING COMMAND: pop i2<br>
Value popped: 150<br>
PROCESSING COMMAND: pop i2<br>
ERROR: This list is empty!<br>
PROCESSING COMMAND: push dHelloWorld 3.1415<br>
PROCESSING COMMAND: push dHelloPlanet -60.5<br>
PROCESSING COMMAND: push dHelloWorld -1<br>
PROCESSING COMMAND: pop dHelloWorld<br>
Value popped: -1<br>
PROCESSING COMMAND: pop dHelloPlanet<br>
Value popped: -60.5<br>
PROCESSING COMMAND: pop sR2D2<br>
ERROR: This name does not exist!<br>
PROCESSING COMMAND: create sR2D2 queue<br>
PROCESSING COMMAND: pop sR2D2<br>
ERROR: This list is empty!<br>
PROCESSING COMMAND: push sR2D2 123abcDEF<br>
PROCESSING COMMAND: push sR2D2 G4H5I6j7k8l9<br>
PROCESSING COMMAND: pop sR2D2<br>
Value popped: 123abcDEF<br>
PROCESSING COMMAND: pop sR2D2<br>
Value popped: G4H5I6j7k8l9<br>
PROCESSING COMMAND: pop sR2D2<br>
ERROR: This list is empty!<br>
PROCESSING COMMAND: pop dHelloWorld<br>
Value popped: 3.1415<br>
PROCESSING COMMAND: pop dHelloWorld<br>
Value popped: 3.14<br>
PROCESSING COMMAND: pop dHelloWorld<br>
ERROR: This list is empty!<br>
