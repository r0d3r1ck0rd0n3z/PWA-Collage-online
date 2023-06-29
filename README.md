# PWA Collage Lite online
My attempt at creating a PWA version of an online collage maker. 
* Assemble up to 4 images into a collage.
* Use gestures to zoom in/out.
* Download collage as a JPG. 
* Installable as a standalone app in Android and Windows. 
* Works offline.
* JavaScript only.

You can test at: <br>
https://r0d3r1ck0rd0n3z.github.io/PWA-Collage-online/index.html

<br>

## Mouse support

For a version that supports mouse-scroll, see: <br>
https://r0d3r1ck0rd0n3z.github.io/PWA-Collage-online/mouseScroll.html

However, bugs:
* Zoom control (scroll amount) dependent on OS settings.
* On mobile, pinch function non-reponsive after one gesture.
* Unstyled. I just wanted to try compiling the scroll version.

<br>

## Backend


### PinchZoom.js 
https://github.com/manuelstofer/pinchzoom <br>
PinchZoom is a Javascript library providing multi-touch gestures for zooming and dragging on any DOM element.

### html2canvas
https://github.com/niklasvh/html2canvas <br>
Renders current page as a canvas image, by reading the DOM and the different styles applied to the elements.

<br>

## Lessons / Improvements(?)

* If installed, takes about less than 500kb. Maybe smaller if webfont was removed, since it's the biggest file. However, some Android phones only have the Roboto font so had to resort to Google fonts.
* Had to copy the JS files to the repository since fetching them from the CDN uses an opaque request, which balloons their file sizes to an unpredictable number.
* Created this since I find myself creating collages every week or so. All of the collage apps on the gPlay store took up MB of space, and my phone has very limited internal storage.

<br>
<br>
