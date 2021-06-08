# implementing_circleCI
this repo will help me to learn how to implement circle CI and how to use it in future

if you cloned this repo just run yarn in your terminal.
Else folder the steps below to create yours.

first
create a directory in your computer called implementing_circleCI. note you can name it anything.

second
open up the folder you created in your favorite text editor. Here i am using VS code

third
In your terminal Run yarn init -y to create a package.json file

fourth
Run yarn add --dev jest to install the jest package for the test. 

fifth
inside the root folder create a file called sum.js

sixth
still inside the root folder create a folder called __Test__

seventh
inside the __Test__ folder create a file called sum.test.js. Note: This can be any name but it must end with .test.ts

eighth
copy and paste the code for the two files

ninth
in your package.json add the 
"scripts": {
    "test": "jest"
}

tenth
Run yarn test in your terminal.