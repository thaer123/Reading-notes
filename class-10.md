# Error Handling & Debugging
<p>
<br>
When you are writing JavaScript, do not expect to write it perfectly the first time.<br>
Programming is like problem solving: you are given a puzzle and not only do you have to solve it,<br>
but you also need to create the instructions that allow the computer to solve it, too.<p>
<p>
When writing a long script, nobody gets everything right in their first attempt.
The error messages that a browser gives look cryptic at first,
but they can help you determine what went wrong in your JavaScript and how to fix it. In this chapter you will learn about:
<p>
<p>
THE CONSOLE & DEV TOOLS
Tools built into the browser that help you hunt for errors.

COMMON PROBLEMS
Common sources of errors, and how to solve them.

HANDLING ERRORS
How code can deal with potential errors gracefully.


ORDER OF EXECUTION
To find the source of an error, it helps to know how scripts are processed.
The order in which statements are executed can be complex;
some tasks cannot complete until another statement or function has been run:
<p>
 <img src="https://www.oreilly.com/library/view/javascript-and-jquery/9781118531648/images/p452-001.jpg" width="350" title="hover text">

This script above creates a greeting message, then ...
