<!DOCTYPE html>
<html>
  <head>

  </head>
  <body>
    <h1>Introduction</h1>
    <p>This is a C++ String Manipulation program that encountered some challenges during development, specifically with the "ChangeToLowerCase" function. After running this function, the program would show the original string but did not provide the lowercase value next to it as it should behave.</p>
    
<h2>Solution</h2>
<p>After some research, it was found that the ASCII table was built in such a way that a lowercase letter has the same value of its equivalent uppercase letter plus 32 (Vice-Versa -32). After modifying the lowercase function from -32 to +32 which is used to generate the lowercase value, the program now produces the lowercase value as it should behave.</p>

<p>However, another problem was found with the "ChangeToLowerCase" function, where the program interpreted a user input "space" to be an "@" symbol. This was due to the following line of code: "if(orinigalString[i]<=97” not being specific enough to specify the user’s input ‘space’ in terms of the ASCII table. After changing the code to as follows: “if(orinigalString[i]<=90&&originalString[i]>65)” the program was able to interpret and output the user’s input ‘space’ correctly.</p>

<p>From looking at the ASCII table, the program was debugged by defining the integers which should be greater or less than or equal to within the "ChangeToUpperCase" and "ChangeToLowerCase" functions.</p>

<h2>Conclusion</h2>
<p>The experience of developing this C++ String Manipulation program has highlighted the importance of thorough research and the use of other resources such as books to assist in understanding strings and how to manipulate them. This will enable further development of programming skills and knowledge to code at a reasonably high level.</p>

<h2>Credits</h2>
<p>This script was created by Anthony Constant (AC). If you have any questions or suggestions, you can contact him at <a href="https://anthonyconstant.co.uk/">https://anthonyconstant.co.uk/</a></p>

<h2>License</h2>
<p>This script is released under the MIT License. See the LICENSE file for more details.</p>
