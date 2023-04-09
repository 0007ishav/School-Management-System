**README**

This README file provides instructions for running a C++ program created in VS Code. This program was created using the C++ extension in VS Code and compiled using the GNU GCC compiler.


**Installation**

To run this program, you must have the following software installed on your machine:

1. Visual Studio Code
2. C++ extension for VS Code
3. GNU GCC compiler


You can download and install Visual Studio Code from here(https://code.visualstudio.com/Download).

After installing VS Code, you can install the C++ extension by following the instructions here(https://code.visualstudio.com/docs/languages/cpp).



To install the GNU GCC compiler, you can follow the instructions provided by the website of the GCC project.

*For Windows users, you can download an installer from here(https://gcc.gnu.org/install/binaries.html) and follow the installation wizard.

*For macOS users, you can install GCC via Homebrew, a popular package manager for macOS, by running the following command in the terminal:

     brew install gcc
  
*For Linux users, you can install GCC from your distribution's package manager. For example, on Ubuntu, you can install the compiler by running the following command:
    
    sudo apt-get install build-essential

Once the installation is complete, you can verify that GCC is installed properly by running the following command in the terminal:
     
     gcc --version
      
      
**Usage**

To run the program, follow these steps:

1. Open Visual Studio Code and open the folder containing the program files.
2. Open the terminal in VS Code by clicking on Terminal -> New Terminal.

3. Compile the program using the following command:
  
     g++ -o main main.cpp
   
This will create an executable file named main.

4. Run the program using the following command:
 
     ./main
  
This will execute the program and display the output in the terminal.
