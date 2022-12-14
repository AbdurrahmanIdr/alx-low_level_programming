# C - Dynamic libraries

In this project, learned about using dynamic libraries in C, including how to create
them and how to use them with `$LD_LIBRARY_PATH`, `nm`, `ldd`, and `ldconfig`.

 **1. Without libraries what have we? We have no past and no future**
  * [1-create_dynamic_lib.sh](./1-create_dynamic_lib.sh): Bash script that creates a
  dynamic library called `liball.so` from all the `.c` files in the current directory.

* **2. Let's call C functions from Python**
  * [100-operations.so](./100-operations.so): C dynamic library containing basic C
  mathematical operation functions that can be called from Python.
  * Includes:
    * `int add(int a, int b);`
    * `int sub(int a, int b);`
    * `int mul(int a, int b);`
    * `int div(int a, int b);`
    * `int mod(int a, int b);`
