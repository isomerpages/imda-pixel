---
title: Code Template
permalink: /documentation/code-template/
description: ""
---
*Last updated on 25 Nov 2022 by Cherina Yee*
# Code Crash Course
## Hello World!

#### How is content written? Using **HTML**
Examples:
  * Header 1: ```<h1></h1>```
  * Link: ```<a></a>```
  * Table: ```<table><tr><td></td><td></td></tr></table>```
  * Line break: ```<br>``` (no need closing bracket)
  
Notes:
* These ```<> </>``` are called HTML tags
* Content is written between the opening and closing tags ```<h1>Hello World</h1>```
* Not all HTML tags need an opening ```<>``` and corresponding closing bracket ```</>```.  A notable eg is ```<br>```. 


#### How are aesthetics taken care of? Using **CSS**
  * text color: 

#### How to combine both? There are 3 methods: 
	* Inline - by using the ```<style>``` attribute inside HTML elements
	* Internal - by using a ```<style>``` element in the ```<head>``` section
	* External - by using a ```<link>``` element to link to an external CSS file
	* **In our case, we are using inline**. External is out as we cannot link to another file, internal is possible but it somehow doesn't work for all HTML tags in Isomer.
	* This is how HTML with inline CSS looks like: ```<a style="color:red;"></a>```. The style appears inside the first <>

Useful HTML code:

All tags 


## Button
Copy below code for this button <a style="background-color: #0A66C2; color: white; text-decoration: none; border-radius: 100px; padding-left: 20px; padding-right: 20px; padding-top:8px; padding-bottom:8px" target="_blank" href="https://www.google.com">Click Me</a>