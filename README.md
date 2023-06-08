# C++ String Manipulation Program

This repository contains a C++ program for string manipulation that encountered some challenges during development. Specifically, the "ChangeToLowerCase" function did not provide the expected lowercase value next to the original string when executed.

## Introduction

The program is designed to manipulate strings in C++. However, the "ChangeToLowerCase" function did not behave as intended. After running the function, the program displayed the original string but failed to provide the corresponding lowercase value.

## Solution

After conducting research, a solution was found based on the ASCII table. It was discovered that a lowercase letter's ASCII value is equal to the ASCII value of its equivalent uppercase letter plus 32 (or vice versa, minus 32). To address the issue, the "ChangeToLowerCase" function was modified to add 32 to the ASCII value, resulting in the correct generation of the lowercase value.

Another problem was identified with the "ChangeToLowerCase" function. The program misinterpreted a user input of "space" as an "@" symbol. This occurred due to an inadequate condition in the code, specifically the line "if(orinigalString[i]<=97". To resolve this, the code was updated to be more specific by using the following condition: "if(orinigalString[i]<=90&&originalString[i]>65)". With this modification, the program correctly interpreted and outputted the user's input of "space".

The debugging process involved analyzing the ASCII table and defining the appropriate conditions within the "ChangeToUpperCase" and "ChangeToLowerCase" functions.

## Conclusion

Developing this C++ String Manipulation program provided valuable insights into the importance of thorough research and utilizing additional resources such as books to enhance understanding of string manipulation techniques. This experience contributes to the further development of programming skills and knowledge, enabling coding at a higher level of proficiency.

## Credits

The C++ String Manipulation Program was created by [Anthony Constant](https://anthonyconstant.co.uk/).

## License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).

## Support My Work

If you like this repository or have used any of the code, please consider showing your support:

- Give it a star ⭐️ to acknowledge its value.
- You can also support me by [buying me a coffee ☕️](https://ko-fi.com/W7W144CAO).

