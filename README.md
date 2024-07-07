# C# Compiler Simulation

## Overview
This project is a simulation of a compiler implemented in C#. It is designed to demonstrate the basic functionalities of a compiler, including lexical analysis, syntax analysis, and code generation. The project includes a graphical user interface (GUI) for interacting with the compiler simulation.

## Features
- **Lexical Analysis**: Tokenizes the input source code into a sequence of tokens.
- **Syntax Analysis**: Parses the tokens to check for grammatical correctness based on a predefined grammar.
- **Code Generation**: Translates the parsed tokens into intermediate code or another form of output.
- **GUI**: Provides a user-friendly interface for inputting source code and displaying the results of the compilation process.

## Project Structure
The project is organized into the following directories and files:

- `Compiler/`
  - `Compiler.sln`: Solution file for the project.
  - `Compiler/`: Contains the main compiler project files.
    - `App.config`: Configuration file for the application.
    - `Compiler.csproj`: Project file.
    - `Program.cs`: Main entry point of the application.
    - `formCompiler.Designer.cs`: Designer file for the compiler form.
    - `formCompiler.cs`: Implementation of the compiler form.
    - `formCompiler.resx`: Resource file for the compiler form.
    - `Properties/`: Contains project properties.
    - `Resources/`: Contains resources used by the application.
    - `bin/`: Output directory for compiled binaries.
    - `obj/`: Intermediate object files and build artifacts.

- `sample java files/`: Contains sample Java files used for testing the compiler simulation.

## Getting Started
To get started with the project, follow these steps:

1. **Clone the repository**:
    ```sh
    git clone <repository-url>
    ```

2. **Open the solution**:
    Open the `Compiler.sln` file in Visual Studio.

3. **Build the project**:
    Build the solution to restore dependencies and compile the project.

4. **Run the application**:
    Start the application from Visual Studio. The main form of the compiler simulation will be displayed.

5. **Test the compiler**:
    Use the provided sample Java files or input your own source code to test the compiler's functionality.

## Requirements
- **Visual Studio**: This project requires Visual Studio for building and running the application.
- **.NET Framework**: Ensure that the .NET Framework is installed on your machine.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contributions
Contributions are welcome! Please fork the repository and submit pull requests for any enhancements or bug fixes.

## Contact
For any questions or inquiries, please contact me at ariessalvador@skiff.com.

