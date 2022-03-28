## Codes using OpenMP directives

### To install Open on MacOS Monterey M1 I used the following commands:

```
brew install gcc
brew install libomp
brew info gcc (To find out which version of GCC was installed) 
```

### To run the program, use the following commands:


```
gcc-11 -fopenmp <file-name>.c -o <file-name>
export OMP_NUM_THREADS=8 (To set the number of threads you want)
./<file-name> 
```
  
Example:
 
 - To run the hello_world.c file, I used:
    
  ``` 
  gcc-11 -fopenmp hello_world.c -o hello_world
  export OMP_NUM_THREADS=8 
  ./hello_world
  ```
  
### List of Programs in this Repository:
  
1. Hello World
2. Fibonacci and Factorial with OpenMP directives
 
