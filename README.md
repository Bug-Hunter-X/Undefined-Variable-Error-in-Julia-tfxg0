# Julia Undefined Variable Bug
This repository demonstrates a common error in Julia: attempting to use an undefined variable.  The `bug.jl` file contains code that throws an error because it references a variable before it is defined. The `bugSolution.jl` shows how to correct this error. 

## Running the Code

1. Save the code in `bug.jl` and `bugSolution.jl` files.
2. Open a Julia REPL.
3. Navigate to the directory where you saved the files using `cd`.
4. Run `include("bug.jl")` and `include("bugSolution.jl")` separately to see the error and its solution.
