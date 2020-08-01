# BrainFC
Welcome to BrainFC!

BrainFC is a BrainF interpreter written in C! 

`main.c` contains the main source code for the interpreter. Additionally, there is a compile-and-run script at `brainf.sh` that can be used to quickly compile and run a BrainF program! There is also an example program at `example.bf` that runs the fibonacci sequence to test out the interpreter! To run the example, simply run one of the following commands:
- `sh brainf.sh example.bf`
- `./brainf.sh example.bf` (given proper permissions to `brainf.sh`)
- `bash brainf.sh example.bf` (if you want to use `bash` instead of `sh`)
- `./brainf example.bf` (if you have already compiled the C source code)


**Note**: This is not cross-platform yet and only supports Linux due to modifications that were required to the `,` command in BrainF to receive input properly in a Linux shell. Additionally, the compile-and-run script uses `clang` which is not available on Windows. 
