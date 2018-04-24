# swapimagesonhover
A custom jQuery script to help you swap one image to another on hover easily using (jQuery, CSS)...

### Usage
The "**swim**" class is ideal for use on images you would want swapped with another on a website. Very useful for e-commerce websites and fancy photo/gallery websites.

### Requirements
jQuery.js

#### Image Styling
The **data-img** attribute is used to attach the second image of your choice you would want swapped. Once this is done, simply add your **swim** class to the image element and you're good to go (**make sure jQuery script is included it requires it to work properly**). Here's a sample below...
```
<!DOCTYPE html>
<html>
<head>
  <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.3.1/jquery.min.js"></script>
  <link href="swapimagesonhover.css" rel="stylesheet" type="text/css"/>
  <script src="swapimagesonhover.js" type="text/javascript"></script>
</head>

<body>
  <img src="image1.jpg" data-img="image2.jpg" class="swim"/>
</body>
</html>
```

### Contributions
Anyone and everyone is welcome to contribute. 
