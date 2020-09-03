# Adding comments
#### Programming languages offer an option of leaving notes for yourself or others. The JavaScript comment feature simplifies the production of more readable code.

#### Comments in JavaScript are used to explain the code and make the program more readable for developers.
#### In programming, comments can also be used to prevent some code lines from being executed. This is useful when testing.
#### There are single-line comments (which comment out one line or a part of one line) and multi-line comments (which comment out a block of code).
#### Multi-line comments are more often used for formal documentations.
#### Comment vs. Comment Out
#### The JavaScript commenting out means that you take a part of the code and surround it with JavaScript comment symbols. Comments are not #### executed by the browser, which means that they won't be displayed.

#### In the following examples, you can see the comments are in light green color.

#### Single-line Comments
#### Single-line comments are used to comment a part of a line or a full line of code in JavaScript. You can use it for either explaining the code #### or debugging (commenting out to prevent the execution by the browser).

#### For a single-line comment, you have to write two forward slashes: //. Anything that goes after // up until a line break is treated as a #### JavaScript comment and not executed as code.

comments.PNG

#### Multi-line Comments
#### JavaScript multi-line comment has the same purpose as a single-line comment. JavaScript comment block starts with two symbols: /*. To end the #### comment, use these symbols */ again. Everything between these symbols will be treated as a comment in JavaScript.

#### You can use JavaScript multi-line comment for leaving a long comment or commenting out larger parts of code while debugging:

#### comment multi lines.PNG

#### Note that when you start with the symbols /*, you must close it with the symbols */. Otherwise all of the code after /* will still be #### commented out. See the following error:

#### comment errors.PNG

#### Source: https://www.bitdegree.org/learn/javascript-comment