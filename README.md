# String Length Calculator

## Description
This is a simple C program that prompts the user to enter a text string, calculates the length of the string, and then prints the length. It serves as a basic example of string manipulation in C.

## Getting Started
To run this program, you'll need a C compiler installed on your system.

1. Clone this repository or download the `string_length_calculator.c` file.
2. Open a terminal or command prompt and navigate to the directory where the file is located.
3. Compile the program using your preferred C compiler. For example:
   ```bash
   gcc string_length_calculator.c -o string_length_calculator
   
1 . Run the compiled executable:
```
./string_length_calculator
```
2. Follow the on-screen instructions to enter a text string.

## Example
```
Enter Your Text Here : Follow_me
9
```
## Notes
- This program assumes that the input string will not exceed 99 characters (excluding the null terminator).
- It uses the `strlen()` function from the `<string.h>` library to calculate the length of the string.

 ## Further Improvements
- **Error Handling**: Implement error handling to ensure the input string does not exceed the array size.
- **Buffer Overflow Prevention**: Modify the `scanf()` function to include the maximum length to prevent buffer overflow.
- **Input Handling**: Consider using `fgets()` to read the input string to handle spaces and avoid buffer overflow.
- **Code Comments**: Include comments throughout the code to explain the purpose of each section for better readability and maintainability.
- **Testing**: Thoroughly test the program with various input strings to ensure it behaves as expected under different scenarios.



