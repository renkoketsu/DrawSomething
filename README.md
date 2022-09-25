## Introduction:

The purpose of this web application is to be able to create simple
drawings utilizing html canvas and javascript. These drawings can be 
downloaded locally onto your PC.

This website was created using the reimg library for the downloading
functionality. This can be found here: https://github.com/gillyb/reimg

## How to Use:

This webpage was tested using Apache 2.4. Downloads for Apache 2.4 can be 
found at https://httpd.apache.org/download.cgi.

Once downloaded, place the files **index.html**, **styles.css**, and 
the **scripts** folder into the directory where the default index
page is located. By default, on Linux and Windows which this was tested
on, this location can be found at */var/www/html* and 
*C:/Apache24/htdocs* respectively.

The webserver can be started on Linux by using the command 
*sudo systemctl start apache2*, and it can be started on Windows
by using the command *httpd.exe* in a command line opened within the
*C:/Apache24* folder.

Now the webpage can be loaded by typing localhost into the address bar
of any modern browser. This website was tested on Firefox, Chrome, and
Brave Browser.

## Planned Future Functionality:

*- A share button to be able to share the canvas as an image to common
social media platforms.*

*- A line tool for creating straight lines.*

*- Support for mobile phones and more obscure viewports.*

## Currently Known Bugs:

*- Canvas size gets defined when loading the page, but doesn't currently 
dynamically change. Attempting to do so makes the canvas break.*

*- Different operating systems change the background of the image when
downloaded. Windows has a black background while Linux has a transparent
one.*

*- Draw Something header in h1 is cut off a little bit*
