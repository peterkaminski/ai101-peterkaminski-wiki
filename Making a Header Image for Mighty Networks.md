# Making a Header Image for Mighty Networks

For Mighty Network event post header images, they specify an aspect ratio of 21:9.

Equivalent aspect ratios are 7:3 (divide both numbers by 3) and 28:12 (multiply 7:3 by 4, so we can divide by 4 later).

Further, they note that the bottom 1/4 of the image may be covered, so don't put anything important there.

My (Pete) trick is to use Midjourney to generate an image in the top 3/4 of the 28:12 frame (use `--ar 28:9`), so Midjourney will frame the subjects well, then generatively fill the bottom 1/4 - perhaps with Midjourney, perhaps with another tool like Photoshop.

Right now I use Photoshop for the generative fill, because I don't know how to tell Midjourney I want to "fill the bottom 1/4 and end up with an aspect ratio of 28:12". It's easy with the crop/expand tool in Photoshop (although Photoshop is not always great at generative fill).

Example:

## 28:9

![[peterkaminski_ae186662-4202-4b29-9e22-d180877a74811.png]]

## 28:12 == 7:3 == 21:9

![[peterkaminski_ae186662-4202-4b29-9e22-d180877a74811.jpg]]

## As rendered on Mighty Networks
![[peterkaminski_ae186662-4202-4b29-9e22-d180877a74811-mighty-networks-screencap.png]]