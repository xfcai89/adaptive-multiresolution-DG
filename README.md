# adaptive multiresolution DG

This is an adaptive multiresolution discontinuous Galerkin (DG) C++ package for solving partial differential equations in high dimensions.

  

## Papers

- Solving transport equations: [SIAM J. Sci. Comput.](https://epubs.siam.org/doi/abs/10.1137/16M1083190)
- Adaptive collocation methods: [arxiv](https://arxiv.org/abs/1912.03982)
- Solving nonlinear conservation laws: [arxiv](https://arxiv.org/abs/1906.00829)
  

## Build Requirement:

Complier: GCC 9.3.0

  

## Run Example:

  

**Compile and link all the program in the example directory**:

  

```sh

make

```

Using this command, all the executable files will be generated in the bin directory and their symbolic link will be generated in the local home directory.

  

**Run program generated by example/FileName.cpp**:

  

```sh

./FileName

```

or

```sh

./bin/FileName

```

  

**Clean**:

  

```sh

make clean

```

  

**Generate Doxygen documentation**:

```sh

make doxygen

```

  

## Project Stucture:

  

**bin**: The output objects executables go here, for the applications, examples and tests.

  

**build**: This folder contains all object files to generate the library, and is removed on a clean.

  

**doc**: Any documents including LaTeX files and also code documents are here; generated doxygen files are in the html subdirectory.

  

**example**: The source files for all the numerical examples.

  

**include**: All project header files. All necessary third-party header files that do not exist under /usr/local/include are also placed here.

  

**lib**: Any libs that get compiled by the project (currently the libsgdg shared library), third party or any needed in development.

  

**source**: The source files to generate the library.

  

**deps**: files of dependency, automatically generated by makefile; removed on a clean.

  

**test**: The source files for unit tests.

  

**script**: scripts including python code for plot