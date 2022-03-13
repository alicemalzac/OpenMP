## Código usando as diretivas do OpenMP 

### Para instalar o Open no MacOS Monterey M1 utilizei os seguintes comandos:


```
brew install gcc
brew install libomp
brew info gcc (Para descobrir qual versão do GCC foi instalado) 
```

### Para rodar o programa é necessário utilizar os seguintes comandos:


```
gcc-11 -fopenmp <nome-do-arquivo>.c -o <nome-do-arquivo>
export OMP_NUM_THREADS=8 (Para setar o número de threads que deseja)
./<nome-do-arquivo> 
```
  
Exemplo: 
 
 -  Para rodar o arquivo hello_world.c, utilizei:
    
  ``` 
  gcc-11 -fopenmp hello_world.c -o hello_world
  export OMP_NUM_THREADS=8 
  ./hello_world
  ```
  
### Lista de Programas nesse Repositório:
  
1. Hello World
2. Fibonacci e Fatorial com diretivas OpenMP  
 
