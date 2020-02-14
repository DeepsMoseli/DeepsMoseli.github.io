---
layout: essay
type: essay
title: What you need to write perfect code: standards!
# All dates must be YYYY-MM-DD format!
date: 2020-02-13
labels:
  - ESLint
  - Coding-standards
---
<br>
Computer programs are prone to syntax, runtime and logical errors, all of which can and should be avoided. While some errors are easy to detect and avoid, especially for an experienced programmer, the task of avoiding bugs in code is non-trivial to new developers. Although errors lead to programs that either don't work or don’t perform their intended task as expected, they are not the only class of bad programming. Without a clear and concise guideline on how to write code that works and is also readable, software development becomes a very difficult task especially for big projects. It is for these reasons that the computer science community has overtime agreed on certain conventions that make the process of developing quality code easier: the coding standards.
<br>

<br>
Although there are general standards for writing in code in any language, such as proper and descriptive naming of functions and variables, there are also language specific guidelines that are updated on an ongoing bases for most languages. For JavaScript, ESLint is a tool that can be used to detect and enforce deviations from the JavaScript coding standards. This tool helps you not only avoid making syntactical errors, but is also able to follow minor logical faults and flag them that would be very hard to debug. for example:
<br>

<br>

```javascript
for(let i=1;i<10;i--){
  statement 1;
  statement 2;
  }
```
<br>
<br>
The code above might look perfectly fine and you wonder why it’s not working, and then go on to spend 30 minutes trying to figure out why before switching to using a while loop in defeat. The loop runs forever because _i_ is heading in the wrong direction. ESLint would be able to flag this fairly easily, and that’s why everyone should use it. It gets you into the habit of putting spaces where it is appropriate so that your code is generally mor readable and more pleasing to look at. Also, when code is more readable and standard, it is easier for large projects to have multiple people contribute to the code and at the end it looks like one person wrote the code. I think that’s powerful for sustainability of code. I personally love it, I found that correcting it's suggestions at the moment it detects a violation on the code block I am currently working on works best. This is oppossed to writting out all your code and then having to go back and fix everything, now you have 20+ things to fix and some depend on each other so you can easily get overwhelmed.
<br>
<br>
If you are not using ESLint already in your projects, I'd love to hear your debugging horror stories. 
  
---
