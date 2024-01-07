            Programming: 

The process of creating a set of instructions that can be executed by a computer to perform a specific task or solve a problem.


            Programming Languages: 

Formal languages with a defined syntax and semantics used to write programs. Examples include C++, Python, Java, and JavaScript


            DOS (Disk Operating System)

DOS (Disk Operating System): An early operating system primarily used on IBM PC-compatible computers. Basic commands for DOS include:

* dir: Lists files and directories.

* cd: Changes the current directory.

* copy: Copies files.

* del: Deletes files.


                Compiler and interpreter

Compiler, Interpreter, Loader, and Linker Fundamentals in C++:

* Compiler: Translates high-level source code (e.g., C++) into machine code (binary executable).

* Interpreter: Reads and executes code line by line, translating each line into machine code at runtime.

* Loader: Loads the compiled machine code into memory for execution.

* Linker: Links multiple object files to create a single executable file.

            Basic Structure of C++

 * #include <iostream> // Include necessary libraries

using namespace std;

int main() {
    // Your code here

    return 0; // Return 0 to indicate successful program execution
} * 

            Data Types:

Data types specify the type of data a variable can hold. Common data types in C++ include:

* int: Integer data type (size- 4 byte).

* float: Floating-point data type (size- 4 byte)

* double: floating point number (size- 8 bytes)

* char: Character data type (size- 1 byte).

* bool: Boolean data type (size- 1 byte) .

            Printing function 

* # include <iostream>
using namespace std;
int main() {
    cout<<"Hello world" ;
    return 0;
* }


            Input Function

* # include <iostream>
using namespace std;
int main() {
    string name;
    
    cout<< "Enter your name : ";
    cin>>name; // we use >> for input 
    cout<< "Your name is "<<name;
    return 0;
* }

            If else statements 

* # include<iostream>
using namespace std;
int main() {
    int age;
    cout<< "Enter your age" <<endl;
    cin >> age;
    
    if(age<18){
        cout << "Your are a child "<< endl;
    }
    else{
        cout << "You are an adult" << endl;
    }
    return 0;
* }            

            Functions in C++:

* Definition: A function is a self-contained block of code that performs a specific task. It can take inputs,
perform calculations, and optionally return outputs.

Purpose:

* Code reusability: Functions can be called multiple times from different parts of the program, 
reducing code duplication and promoting modularity.

* Better organization: They break down complex programs into smaller, more manageable units, making code easier to read, understand, and maintain.

            
            Types of Functions:

* Based on Return Value:

Void functions: Don't return any value. Used for performing actions (e.g., printing to the screen).
Functions with return values: Return a value of a specific data type after execution.
Based on Parameters:

* Parameterized functions: Take arguments (inputs) to perform calculations or operations.
Non-parameterized functions: Don't take any arguments.
Based on Definition:

* Built-in functions: Predefined functions provided by the C++ standard library (e.g., sqrt, pow, sin, cos).
User-defined functions: Functions written by the programmer to perform specific tasks.

        Example of using functions 

* # include <iostream>
using namespace std;
int adding_num(int a , int b){ // declaring the function
    int c = a+b;
    return (c);
}
int main() {
   int d = adding_num(10,3); // calling the function
    cout <<"The result is " <<d;
    return 0;
* }