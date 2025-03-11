# SE-assignment2

README.md

# Simple Greeting Program

This is a basic C++ program that takes a user's input (their name) and prints a greeting message.

# Features:

Accepts user input
Outputs a personalized greeting
Uses standard C++ libraries

# Installation: 

Ensure you have a C++ compiler installed (e.g., g++ for Linux/macOS or MinGW for Windows).
Clone this repository or create a new file called main.cpp and paste the code below.

# Usage:

Compiling and Running the Program:

# Using g++:

g++ -o greeting main.cpp
./greeting

# Using clang++:

clang++ -o greeting main.cpp
./greeting
Code
cpp

#include <iostream>
using namespace std;

int main() {
    string name;
    cout << "Enter your name: ";
    cin >> name;
    cout << "Hello, " << name << endl;
    return 0;
}

# Example Output:

yaml

Enter your name: John
Hello, John

This program reads user input and prints a greeting message accordingly.
