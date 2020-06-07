# stack-vm
Stack Virtual Machine using C++

## Go to sasm (Stack Assembler) directory and do
make\
./sasm test.sasm 

## Go to stack-vm directory and do
make\
./stack-vm ../sasm/out.bin

## Output for test.sasm
top: 3\
top: 4\
add 3 4\
top: 7\
top: 2\
mul 7 2\
top: 14\
top: 2\
add 14 2\
top: 16\
top: 4\
div 16 4\
top: 4\
halt\
top: 4
