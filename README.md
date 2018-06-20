# JSAgeCheckerProject
Build a pop up in JavaScript that will ask the user's age and respond.

<b>Project Step by Step: Build an Age Checker for a Brewery Website</b>

1. Download the <a href="https://github.com/LibraryCodeLab/JSAgeCheckerProject/blob/master/index.html">HTML</a> & CSS Files. Look at the code in your HTML file and your CSS file to make sure you understand how it is rendering in the browser. 

2. Create a new file in your text editor and save it as <b>script.js</b>. This is where we will write all of our JavaScript code.

3. Link your JavaScript file and your HTML file.  Between the header tags of your HTML document, write the following code:

                              <b><script type="text/javascript src="script.js"></script></b>

4. Now we will create our popup box. First we need to create a variable called age. This will store the user's input to the question "How old are you?"

                             <b>var age=prompt("How old are you?");</b>

5. Save your JavaScript and refresh your page and you should see your popup. You'll notice you can enter in an answer to the prompt, but it doesn't do anything.

6. Next, we will create our if/else statement. This will allow us to use the input to show a different message depending on how the user responds.  We want the popup to show one message if the user is over 21 and a different message is they are under 21. 

Use the format for if else statements:
<b>
if (condition) {
    block of code to be executed if the condition is true
} else { 
    block of code to be executed if the condition is false
}
</b>
Hint: Your parameter will be (age >= 21), which means greater than or equal to 21.

7. Change the text of your alerts. Edit the text of your alerts to say "Welcome!" if your user is 21 or older, or "You must be 21!" if they are under 21.

8. Check your work! Save your JavaScript and refresh your page in the browser to check your work. Enter a number 21 or over and see if it gives you the correct response. Refresh your page to get the pop up to come up again--enter a different number to check your other response. 
