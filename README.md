imgTool, a tool to mess around with pictures, written in JavaScript.

Cause for existence: To be a playground for messing around with JavaScript, 
and maybe create something cool along the way.

Basic operation:

First principle:
All processing must happen client-side, server-side is reserved for holding code
and presenting UI, users pictures should not touch server-side, it should all
be confined to client-side memory and processing power.

With that out of the way:
imgTool is meant as a simple tool to edit picutres. The user adds a .jpg or a
.png file to start the process.

Once the file is loaded into the browser, you get access to a toolbox, allowing
the user to modify the picture in various ways.

Once the user is satisfied with the modifications, she can hit export, and save
her creation back to permanent storage.

This is mainly an exersize in coding for the devs of this project, an attempt to
become more familiar with javascript as a creative tool, and maybe learn a thing 
or two about algorithms in general, and image manipulation specifically.

List of tools we want to implement:

 - Pixel sorting
 - EXIF reader
 - Convert to grayscale
 - Contrast
 - Brightness
 - Hue shift (global)
 - Hue shift (local)
 - Crop


