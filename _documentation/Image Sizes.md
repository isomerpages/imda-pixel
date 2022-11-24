---
title: Image Sizes
permalink: /documentation/image-sizes/
description: ""
---
# Image Sizes
All sizes are written as width x height.

Rule of thumb: Trim the images to just the object, ie. remove all extra white space, before padding it. This will ensure the same width/height to be maintained across multiple images.

## 1. Home Page
* <span style="font-size:1.2em; background:cyan"><b>Final Image size: 1000px by 440px</b></span>
* Image size: 780px by 440px 
* Padding: 110px on left and right

![](/images/Documentation/Homepage.png)

## 2. Facilities
### a. Overview

* <span style="font-size:1.2em; background:cyan"><b>Final Image size: 1200px by 675px</b></span>

![](/images/Documentation/Facilities%20-%20Overview.png)

* Note: There is no need to round the 4 corners, as they are automatically rounded by the CSS code "```border-radius: 15px```". Change the roundness by editing the no. of pixels.
* Code for reference: ```<img src="example.jpg" style="border-radius:15px;">```

### b. Featured Areas - Equipment
* <span style="font-size:1.2em; background:cyan"><b>Final Image size: 500px by 280px</b></span>

Depending on the equipment, different image size and paddings were used.
* **For long images w short height , e.g. VR headsets**:  (a) scale the image to width 420px, then (b) pad the width and height till 500px by 280px
![](/images/Documentation/Equipment_Long.png)
* **For tall images w short width , e.g. immersive accessories**: (a) scale the image to height 210px, then (b) pad the width and height till 500px by 280px
![](/images/Documentation/Equipment_Tall.png)
* **For normal-sized images , e.g. AR/MR headsets**: (a) scale image to width 330px, then (b) pad the width and height till 500px by 280px
![](/images/Documentation/Equipment_Midsize.png)


## 3. Community
### a. Partners
* <span style="font-size:1.2em; background:cyan"><b>Final Image size: 1000px by 440px</b></span>
**Line logos are used.** Stack logos are not used as it will overwhelm those that can only be line (e.g. Grab, IBM, AWS)

### b. Incubatees
All squares of the same size will do. Currently they are sized down to 252px by 252px, but if all the new collected logos are high res, they can be increased.
* <span style="font-size:1.2em; background:cyan"><b>Current Image size: 252px by 252px</b></span> 
![](/images/Documentation/incubatee.png)

### c. Mentors
All squares of the same size will do. Currently they are sized at 230px by 230px.
* <span style="font-size:1.2em; background:cyan"><b>Current Image size: 252px by 252px</b></span> 
![](/images/Documentation/incubatee.png)

## Others
Feel free to use any image size.