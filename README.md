# JSAgeCheckerProject
In this project, we will build a pop up in <a href="https://www.w3schools.com/js/">JavaScript</a> that will ask the user's age and respond. We will use the built in <a href="https://www.w3schools.com/jsref/met_win_prompt.asp">prompt function</a> in JavaScript to create a pop up box that asks the user's age. Using <a href="https://www.w3schools.com/js/js_if_else.asp">if/else logic</a>, we will program the popup box to respond "Welcome" if the user enters a number 21 or over, and "You must be 21!" if not.
<hr>
<p>
1. Download the <a href="https://github.com/LibraryCodeLab/JSAgeCheckerProject/blob/master/index.html">HTML</a> & <a href="https://github.com/LibraryCodeLab/JSAgeCheckerProject/blob/master/style.css">CSS</a> Files. Look at the code in your HTML file and your CSS file to make sure you understand how it is rendering in the browser. 

2. Create a new file in your text editor and save it as <b>script.js</b>. This is where we will write all of our JavaScript code.

3. Link your JavaScript file and your HTML file.  Between the header tags of your HTML document, write the following code:

                              <b><script type="text/javascript" src="script.js"></script></b>

4. Now we will create our popup box. First we need to create a variable called age. This will store the user's input to the question "How old are you?"

                             <b>var age=prompt("How old are you?");</b>

<i>Save your JavaScript and refresh your page and you should see your popup. You'll notice you can enter in an answer to the prompt, but it doesn't do anything.</i>

6. Next, we will create our if/else statement. This will allow us to use the input to show a different message depending on how the user responds.  We want the popup to show one message if the user is over 21 and a different message is they are under 21. 
<hr>
<p><b>Use the format for if else statements:</b></p>


<b>
    <p>if (</b><i>condition</i><b>) {</b></p>
    <p><i>block of code to be executed if the condition is true</i></p>
   <b> <p>} else { </p></b>
    <p><i>block of code to be executed if the condition is false</i></p>
   <b> <p>}</p></b>
</b>
<b>Hint: Your parameter will be (age >= 21), which means greater than or equal to 21.</b>
<hr>

7. Change the text of your alerts. Edit the text of your alerts to say "Welcome!" if your user is 21 or older, or "You must be 21!" if they are under 21.

8. Check your work! Save your JavaScript and refresh your page in the browser to check your work. Enter a number 21 or over and see if it gives you the correct response. Refresh your page to get the pop up to come up again--enter a different number to check your other response. 
</p>
<hr>
<b>Helpful Links from Class</b>
<ul>
    <li><a href="https://www.youtube.com/watch?v=nItSSTwBvSU">Video: What is JavaScript?</a></li>
<li><a href="https://www.javascript.com/">JavaScript.com Tutorial</a></li>
<li><a href="https://www.w3schools.com/js/">w3chools: JS</a></li>
<li><a href="https://www.w3schools.com/js/js_syntax.asp">w3chools: JS Syntax</a></li>
<li><a href="https://www.w3schools.com/js/js_datatypes.asp">w3chools: JS Data Types</a></li>
<li><a href="https://www.w3schools.com/js/js_functions.asp">w3chools: JS Functions</a></li>
</ul>
