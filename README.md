<div>
    <h2>Challenges with C++ String Manipulation Program</h2>
    <p>One of the more challenging aspects I found whilst developing the C++ String Manipulation programme was the "ChangeToLowerCase" function. Unfortunately, whilst running this function, the programme would show their original string but did not provide the lowercase value next to it as it should behave. </p>
    <p>However, after some profound research I found the ASCII table was built in such a way that a lowercase letter has the same value of its equivalent uppercase letter plus 32 (Vice-Versa -32). After modifying the lowercase function from -32 to +32 which is used to generate the lowercase value, the programme now produces the lowercase value as it should behave. </p>
    <p>However, there was another problem I found with "ChangeToLowerCase" function for example: when the user entered 'space' the programme interpreted this to be an '@' symbol. I found that the following line of code: "if(orinigalString[i]<=97" is not specific enough to specify the user's input 'space' in terms of the ASCII table. After changing the code to as follows: "if(orinigalString[i]<=90&amp;&amp;originalString[i]&gt;65)" the programme was able to interpret and output the user's input 'space' correctly. From looking at this ASCII table I was able to debug my programme by defining the integers which should be greater or less than or equal to within the "ChangeToUpperCase" and "ChangeToLowerCase" function. </p>
    <p>I will continue to further develop my programming skills and knowledge by doing more profound research and using other resources such as the book I used to assist me in understanding strings and how to manipulate them "C++ Programming Program Design Including Data Structures 7th Edition D.S. Malik" so that I will be able to code at a reasonably high level.</p>
    
 <h2>Credits</h2>
<p>This script was created by Anthony Constant (AC). If you have any questions or suggestions, you can contact him at https://anthonyconstant.co.uk/</p>

<h2>License</h2>
<p>This script is released under the MIT License. See the LICENSE file for more details.</p>
    
    
</div>
