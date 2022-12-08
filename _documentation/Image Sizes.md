---
title: Image Sizes
permalink: /documentation/image-sizes/
description: ""
---
*Last updated on 25 Nov 2022 by Cherina Yee*

# Image Sizes
All sizes are written as width x height.

Rule of thumb: Trim the images to just the object, ie. remove all extra white space, before padding it. This will ensure the same width/height is maintained across multiple images. 

Otherwise, most images have different paddings and simply resizing them will not lead to a consistent look like below.

![](/images/Documentation/same-look-feel.png)

## 1. Home Page
* <span style="font-size:1.2em; background:cyan"><b>Final Image size: 1000px by 440px</b></span>
* Image size: 780px by 440px 
* Padding: 110px on left and right

![](/images/Documentation/Homepage.png)

## 2. Facilities
### a. Overview

* <span style="font-size:1.2em; background:cyan"><b>Final Image size: 1200px by 675px</b></span>

![](/images/Documentation/Facilities%20-%20Overview.png)

* Note: A rectangle image will do. There is no need to round the 4 corners, as they are automatically rounded by the CSS code "```border-radius: 15px```". Change the roundness by editing the no. of pixels.
* Full code for reference: ```<img src="example.jpg" style="border-radius:15px;">```

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
* <span style="font-size:1.2em; background:cyan"><b>Final Image size: 720px by anything  (proportionate scaling)</b></span>
* Image size: 600px by anything (proportionate scaling)
* Pad 60px on left and right
**Line logos are used.** Stack logos are not used as it will overwhelm those that can only be line (e.g. Grab, IBM, AWS)
![](/images/Documentation/partners.png)


### b. Incubatees
* <span style="font-size:1.2em; background:cyan"><b>Final Image size: 252px by 252px</b></span> 
* Scale the logo such that the longer end is 252px. Then, pad the shorter end to 252px 
* All squares of the same size will do. Currently they are sized at 252px by 252px, but if all the new collected logos are high res, dimensions can be increased
![](/images/Documentation/incubatee.png)

### c. Mentors
* <span style="font-size:1.2em; background:cyan"><b>Final Image size: 230px by 230px</b></span> 
* All squares of the same size will do. Currently they are sized at 230px by 230px (downloaded from the old website)


![](/images/Documentation/mentors.png)

* Note: There is no need to crop to a circle, or add a border, as they are automatically done by the CSS code "```border-radius: 50%; border: 10px solid white;```". 
* Full code for reference: ```<img src="example.jpg" style="border-radius: 50%; border: 10px solid white">```

## Others
Feel free to use any image size.