Holds the cover image working files (SVG) and final images for all platforms. This image should also be used in the intro and outro of the promo video, and possibly for the introduction lesson as well.

Skillshare: 1920 x 1080
Udemy: 750 x 422, can't have text

// Use trianglify.io for backgrounds!

// make sure you specify the correct size in the fields on the site
// https://trianglify.io/
var c=document.getElementsByTagName("canvas");
var d=c[0].toDataURL("image/png");
var w=window.open('about:blank','image from canvas');
w.document.write("<img src='"+d+"' alt='from canvas'/>");

Font I typically use: Futura