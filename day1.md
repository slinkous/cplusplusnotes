# Intro to C++: Day 1

## How C++ is written

- the programming language is translated into machine language
- machine language: built-in, primitive instructions
- machine code: literally in binary 

## Two modes of translation

- interpretation: runes one line at a time, translates single line and executes it
- compilation: takes whole file, translates to machine-code file

### Which is faster?
- compiled, because ...?
- C had a fundamental intention of being fast, and C++ was built with that philosophy
- Why it is the language of choice for games
- Under the hood of a lot of compilers, too.

## Operating System
- Most important program in your computer
- When computer starts, it calls on OS to run
- Big piece of software that coordinates all the activities and processes

``` User 
    Application Programs
    OS
    Hardware```

## IDE
- Integrated Development Environment
- Suite: several tools
- For writing, editing C++ source code
- Compiling
- Allows you to manage larger projects, multiple files, libraries, "linkage"

## The process of Programming
1. Requirements
2. Analysis and Design of Algorithms
  - pseudocode (English sentences, not language-specific, imagine communicating with a manager)
  - flowchart (If it's not too large. Very clear way to present idea. Different box shapes for different actions)
3. Coding
4. Testing (Often doing this as your are coding, but then separate testers, sometimes nontechnical, given a program template to work from)
5. Documentation

- When the client is not satisfied, you have to re-evaluate the discussed requirements, and if you did not fulfil them, need tos tart again.
- Adds "regression testing" to requirements as you add more features on top.
- Design stage is where it's at, and pays better

### Skills to develop in this classs
- Good programming habits (building incrementally)
- Programming techniques
  - Procedural programming
    - Top Down design: from largest goal, down through subtasks
    - Bottom-up implementation: tasks are given to separate teams to create and test 
    - Very task-oriented
  - Object-Oriented
    - Look at nouns, each one has a potential to be represented in memory
      - What kind of data should you use?
    - Becomes very data-driven
- Problem solving: apply what you learn
  - Can get suggestions from prof. or determine our own
 
 ## About C++
 - used for systems and applications
 - Evolved from C in 1990's 
  - Bjarne Strousstrup 
  - Created a way to use a class in C
 - Standared Library: precompiled  code to be used in your program.
  - Very useful for vectors, for example
 - Intended to run very fast (ideal for games)
 
 ## Tools used in class
 - IDE does the following
  1. Editor
  2. Compiler
  3. Linker
 - We are using Microsoft Visual Studio: will be available in STEM lab across the hall
 
 > When getting hired, they are looking for someone to train. Not expecting the same tech stack, just looking for problem solving. Prof had to solve a shipping challenge in his first interview.
 
 - Avoid using an online IDE: it will work, up until we have to do I/O
 - Have to be rigorous about deleting code on class machines, we are responsible if someone else plaigiarizes them. 
 - Download Community version of VS
  - Set to Desktop development with C++ (Not Windows or .NET)
  
  ## First program
  
  ```C++
  //Programmer: <your name here>
  //Date:
  //Purpose:
  
  #include <iostream> //tells preprocessor to pull from library - "stream" comes from idea that it would be characters coming in and out
  using namespace std; //tells compiler go to "namespace" place where words are defined. STD stands for "standard"
  //the above are "directives", really intended for preprocessor.
  // in the future, we will learn how to use our own namespace (?)
  
  int main() //return type and indentifier. "main" is case-sensitive. () allow us to pass arguments
  {
    /*
      your work here (multiline comment)
      This is the function body (including the return)
    */
    
    return 0; //status code to the runtime system. Everything has executed normally. 
  }
 
 
 
 
 
