
#Conditional Statements
After the lesson, you will understand:
+ What conditional statements are
+ Why we use them
+ js conditional statement syntax
+ if/else statements
+ if/else if statements
+ Comparison operators
+ Introduction to Logical Operators
+ Syntax

## Conditional statements
Now that we are getting the hang of manipulating our variables, let’s experiment with conditional statements. A conditional statement is a set of commands that executes if a specified condition is true (remember our data type boolean, with a value of true or false?)
```
if (condition){
  statement_1
}
else {
  statement_2
}
```
Let’s make an if/else statement for our var collegeGpa = 4.0
```
if (collegeGpa == 4.0) {
  window.alert('Doing mighty fine!');
} else {
  window.alert('Let's hit the books!');
}
```
Notice the syntax for our conditional statement in JS:
+ conditions are in parenthesis,
+ blocks are in curly brackets {}
+ expressions end with ';' semicolons.

Notice also our use of indentation. JavaScript doesn't need indentation to work, but it makes code way easier to read. When we move to python, the wrong whitespace will break our program, so it’s good to get used to indenting now. Plus, then you can read what's going on!

We can make our if/else statement more complex and more specific by adding an additional conditional statement with else if:
```
if (collegeGpa >= 4.0) {
    window.alert('Doing mighty fine!');
} else if (4.0 > collegeGpa > 3.0) {
    window.alert('Not too shabby!');
} else {
   window.alert('Let's hit the books!');
}
```
You’ll notice we’ve been using some new operators in our conditional statements, like '==' and '>='. These are our comparison operators. Notice the difference between using a single = and the double '=='.

What is the difference? '=' assigns a value, '==' checks if two values are equal.

'==' is one of the **comparison** operators. They let you express conditions like equality and inequality. They evaluate to True or False, so they are really useful in conditional statements.

Here is a list of all of JS comparison operators and what they do

<img src="https://raw.githubusercontent.com/learn-co-curriculum/cssi-2.5-conditional-statements/master/js-boolean-operator-table.png">

We can add even more complexity to our conditional statements with logical operators. These let us combine conditions. Is x greater than 4 AND less than 7?

Here is a list of all the Logical Operators and what they do:

<img src="https://raw.githubusercontent.com/learn-co-curriculum/cssi-2.5-conditional-statements/master/js-logical-operators.png">

##Student Challenge
**Skee-ball Rater**

![Skee-ball](http://robertkaplinsky.com/wp-content/uploads/2013/03/skeeball_cover.jpg)


Create a conditional statement that uses window.alert to show the rating of a Skee-ball player based on their score.

If you’re not up on your Skee-Ball scoring, a score <150, is pretty bad. A score of 150-250 is decent. A score of 250-350 is good. A score between 350-450 is great. A score above 450 is amazing.

Be creative with the messages you write (and let's find some Skee-Ball in the office later!).

<p data-visibility='hidden'>View <a href='https://learn.co/lessons/cssi-2.5-conditional-statements' title='Conditional Statements'>Conditional Statements</a> on Learn.co and start learning to code for free.</p>
