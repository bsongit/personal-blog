---
layout: post
title:  "Working with webp images"
date:   2021-02-09 00:00:00
img: img-formats.webp
description: Improve your web application perfomance working with webp images. 
---

If you are new in web application development, your problely had problems with loading time. This problem affects your position in the Google search results and one of the most common mistakes are on load images.

<b>Let's understand some image formats:</b> 

Images .jpg : 
    This format is good for images with a lot of colors, and it's the main option for static images. But there is usually a downside: you will notice a slight loss of quality when compressing images to jpg.

Images .png: 
    It's excellent maintaining image quality, even if it's already compressed. This format is widely used when it's necessary to remove the image background and is also generally adopted when working with a large number of data or pixels. For example, logo marks, images with many texts and illustrations.Although it doesn't work very well for photograths.

<h2> Finally images .webp</h2>
This image format was developed by Google Inc., has the objective of reducing the file size and ensuring the fastest transfer so that it doesn't have a good connection. Another advantage of Webp is to combine the best part of all formats, surch as file compression (present in JPEG) and the ability to work with alpha pixels (present in PNG). It also supports animations as well as the GIF format.

Webp provides between 25 ~ 34% less image size than PNG or JPEG. it also offers the same quality as the original image, but if you want a smaller size you can specify it in cwebp via command line. 

<h3>Install Webp on Linux: </h3>
    $ sudo apt-get update
    $ sudo apt-get install webp

<h3>Install Webp on Windows:</h3>
    https://developers.google.com/speed/webp/download


<h4>Type this command and covert any image to webp:</h4>
    cwebp -q 50 your_image.jpg -o your_image.webp 

<b>NOTE: If you are in Windows config eviroment variables to 'cwebp'; </b>
