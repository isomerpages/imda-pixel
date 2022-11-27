---
title: Code Crash Course
permalink: /documentation/code-crash-course/
description: ""
---
*Last updated on 25 Nov 2022 by Cherina Yee*
# Hello World

#### How is content written? Using **HTML**
Examples:
  * Header 1: ```<h1>Welcome</h1>```
  * Link: ```<a href="https://www.google.com" target="_blank">Google</a>```
  * Table: ```<table><tr><td>Col1</td><td>Col2</td></tr></table>```
  * Image: ```<img src="file.jpg" alt="Image example">```
  * Line break: ```<br>``` 
  * Span: ```<span></span>``` (use this when you want to style a small portion,  eg. changing <span style="font-size:1.3em">font size</span> or <span style="color:blue;">colour</span> of a part of a text while retaining the main style)
  
Notes:
* These ```<> </>``` are called HTML tags
* Content is written between the opening and closing tags ```<h1>Hello World</h1>```
* There can be multiple HTML tags within a HTML tag. An eg. is the table. 
* Not all HTML tags need an opening ```<>``` and corresponding closing bracket ```</>```.  Notable egs include ```<br>``` and ```<img>```. 


#### How are aesthetics taken care of? Using **CSS**

Examples:
  * <span style="color:red;">text color</span>: ```color: red;``` / ```color:#FF0000;``` / ```color:rgba(255,0,0,0.5);``` - a here refers to alpha which controls the opacity - 0.0 is fully transparent and 1.0 is fully opaque
  * <span style="background-color:#FFFF00;">background color</span>: ```background-color:yellow;```  / ```background-color:#FFFF00;``` / ```background-color:rgba(255,255,0,1);``` 
  * <span style="font-size:1.3em">Font</span> <span style="font-size:0.7em">size</span>: ```font-size: 1.3em;``` - the units I use here is ```em```. By default, the text is 1em (usually 16px). em is used because it's dynamic. Eg. when the screen is smaller, the text will scale accordingly instead of being fixed at a certain pixel value.
  * Centering horizontally: ```text-align: center;```
  * Centering vertically: ```vertical-align: middle;```
  * No underline for <a href="https://ww.google.com" target="_blank">links</a>: ```text-decoration: none; ```. Here you go: <a href="https://ww.google.com" target="_blank" style="text-decoration: none; ">link</a>
  * 

#### How to combine both? There are 3 methods: 
* Inline - by using the ```<style>``` attribute inside HTML elements
* Internal - by using a ```<style>``` element in the ```<head>``` section
* External - by using a ```<link>``` element to link to an external CSS file
	* **In our case, we are using inline**. External is out as we cannot link to another file, internal is possible but it somehow doesn't work for all HTML tags in Isomer.
	* This is how HTML with inline CSS looks like: ```<a style="color:red;"></a>```. The style appears inside the opening tag <>


## Button
Copy below code for this button <a style="background-color: #0A66C2; color: white; text-decoration: none; border-radius: 100px; padding-left: 20px; padding-right: 20px; padding-top:8px; padding-bottom:8px" target="_blank" href="https://www.google.com">Click Me</a>