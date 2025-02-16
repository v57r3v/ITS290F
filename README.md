java cITS290F Human Computer Interaction  User Experience Design
Lab 1. Introduction to CodePen
 
 
What you’ll learn in this lab:
 
• Understanding CodePen
• Creating a front-end page
• Using Google form to submit your lab work
 
 
CodePen is a cloud-based integrated development environment (IDE) for writing and sharing front-end code. It would be useful for us to try out our code in certain lab practices. 
 
 
1. Sign up CodePen  
 
Sign up a CodePen free account
 
1. Visit http://codepen.io .
 
2. Sign up with email or your preferred methods, as shown in Figure 1. 
 
3. Check your mailbox to activate your account, if applicable.
 
4. Login CodePen with your login credentials.
 

FIGURE 1
CodePen sign up page.
 
2. Understanding the CodePen Editor
 
Figure 2 shows the user interface of the CodePen Editor. It consists of 3 editor panels for HTML, CSS and JS that you can edit your code and scripts, and a live preview panel that shows the resulting webpage of your code. 
 

FIGURE 2
CodePen Editor.
 
 
 
TRY IT YOURSELF
 
Taking an Editor Tour
 
CodePen provides an online tutorial for you to get familiar with the user interface of the CodePen editor:
 
1. Go to https://codepen.io/pen/tour/welcome/start .
 
2. Follow the instructions and try it out.
 
 
3. Lab Exercises
 
On your own, spend time becoming familiar with the CodePen interface. For this part, practice creating a Pen and attempting to finish the exercises.
 
You need to answer the follow-up questions and submit your answers (see submission section).
 
 
Exercise 1
 
Create buttons that change the color of an HTML paragraph.
 
1. Create a new Pen.
 
2. Put the following code into the HTML window
 
Hello, World!
Red
 
3. Put the following code into the JS window
function changeColor(color) {
 document.getElementById('hello').style.color=color;
}
 
4. Save and try clicking the “Red” button.<代 写ITS290F 、 java，c++
代做程序编程语言br> 
5. Add two buttons for changing color of “Hello, World” to green and blue.
 
6. Save and try clicking the new buttons.
 
 
Follow-up Questions
 
Q1. How many buttons you see on the screen?
 
Q2. A function is called when you click on the button. What is the name of the function?
 
Q3. The function uses a reference ID to lookup for the HTML 
 element. What is the ID?
 
Exercise 2
 
Learn reading JS reference from w3schools and create buttons that change the font style and weight of an HTML paragraph.
 
1. Continue to work on the code of Exercise 1. Add two buttons for changing the font style of “Hello, World” with Normal and Italic styles.
 
2. Create a new JS function with a parameter called changeFontStyle(style) .
 
3. Study the fontStyle property of JS on w3schools JSreference(https://www.w3schools.com/jsref/prop_style_fontstyle.asp) and complete the function.
 
4. Associate the new function with the corresponding parameters to the onClick event of the new buttons. Save and try clicking the new buttons.
 
5. Add three buttons for changing the font size of “Hello, World” with size “x-large”, “250%”, and “100px”. The outcome of the page should look like the follows:
 

 
6. Create a new JS function with a parameter called changeFontSize(size) . 
 
7. Study the fontSize property of JS on w3schools JS reference /prop_sand complete the function.
 
8. Associate the new function with the corresponding parameters to the onClick event of the new buttons. Save and try clicking the new buttons.
 
 
Follow-up Questions
 
Q4. On the page, which font size property value produces largest font size?
 
Q5. Submit your solution HTML code of Exercise 2. The first line is given to you.
Hello, World!
...
 
Q6. Submit your solution JS code of Exercise 2. The first function is given to you.
function changeColor(color) {
 document.getElementById('hello').style.color=color;
}
 
...

         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
