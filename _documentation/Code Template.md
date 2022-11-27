---
title: Code Template
permalink: /documentation/code-template/
description: ""
---
*Last updated on 27 Nov 2022 by Cherina Yee*

# Button
<a href="https://www.google.com" target="_blank" style="background-color: #0A66C2; color: white; text-decoration: none; border-radius: 100px; padding-left: 20px; padding-right: 20px; padding-top:8px; padding-bottom:8px">Click Me</a> 

```<a href="https://www.google.com" target="_blank" style="background-color: #0A66C2; color: white; text-decoration: none; border-radius: 100px; padding-left: 20px; padding-right: 20px; padding-top:8px; padding-bottom:8px">Click Me</a>```

<a style="background-color: #0A66C2; color: white; text-decoration: none; border-radius: 100px; padding-left: 20px; padding-right: 20px; padding-top:8px; padding-bottom:8px">Application Closed</a>

```<a style="background-color: #0A66C2; color: white; text-decoration: none; border-radius: 100px; padding-left: 20px; padding-right: 20px; padding-top:8px; padding-bottom:8px">Application Closed</a>```

<span style="background-color: yellow;  padding-left: 10px; padding-right: 10px;">Things to change</span>:
* `href`: Hyperlink to the site (remove if you want your button to not link anywhere, eg when Application Closed) 
* `<>Click Me<>`: Button text
* `target="_blank"` opens site in a new tab. Change to "_self" is you want it to open on the current page
* `background-color` if you want to change the button colour
* `color` if you want to change the text colour


# Topics for Workshops
#### Programmes > For Corporates/Startups > Innovation Consultancies
<table>
	<tr>
		<td style="background:#40c1ac; color:white; text-align: center; border: 15px solid white; width:25%;">
			<b>TOPIC</b>
			<br><span style="font-size:0.9em;">Description</span>
			<br><br><a href="eBrochure.pdf" target="_blank" style="color: white;">eBrochure</a><br>
		</td>
		<td style="background:#991e66; color:white; text-align: center; border: 15px solid white; width:25%;">
			<b>TOPIC</b>
			<br><span style="font-size:0.9em;">Description</span>
			<br><br><a href="eBrochure.pdf" target="_blank" style="color: white;">eBrochure</a><br>
		</td>
		<td style="background:#ff8400; color:white; text-align: center; border: 15px solid white; width:25%;">
			<b>TOPIC</b>
			<br><span style="font-size:0.9em;">Description</span>
			<br><br><a href="eBrochure.pdf" target="_blank" style="color: white;">eBrochure</a><br>
		</td>
		<td style="background:#63c8dc; color:white; text-align: center; border: 15px solid white; width:25%;">
			<b>TOPIC</b>
			<br><span style="font-size:0.9em;">Description</span>
		</td>
	</tr>
</table>
Template code:
				
```
<table>
	<tr>
		<td style="background:#40c1ac; color:white; text-align: center; border: 15px solid white; width:25%;">
			<b>TOPIC</b>
			<br><span style="font-size:0.9em;">Description</span>
			<br><br><a href="eBrochure.pdf" target="_blank" style="color: white;">eBrochure</a><br>
		</td>
		<td style="background:#991e66; color:white; text-align: center; border: 15px solid white; width:25%;">
			<b>TOPIC</b>
			<br><span style="font-size:0.9em;">Description</span>
			<br><br><a href="eBrochure.pdf" target="_blank" style="color: white;">eBrochure</a><br>
		</td>
		<td style="background:#ff8400; color:white; text-align: center; border: 15px solid white; width:25%;">
			<b>TOPIC</b>
			<br><span style="font-size:0.9em;">Description</span>
			<br><br><a href="eBrochure.pdf" target="_blank" style="color: white;">eBrochure</a><br>
		</td>
		<td style="background:#63c8dc; color:white; text-align: center; border: 15px solid white; width:25%;">
			<b>TOPIC</b>
			<br><span style="font-size:0.9em;">Description</span>
		</td>
	</tr>
</table>
```

Notes:
* 1 table row, indicated by 1 set of `<tr></tr>`
* 4 columns, indicated by 4 sets of `<td></td>` within table row
* `width:25%` is the size of the column. 4 columns = 100%. Use percentages instead of pixels so column will size accordingly to screen size.