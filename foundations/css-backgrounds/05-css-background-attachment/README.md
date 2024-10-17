# Adding CSS Background attachment property
In this exercise, you're going to practice using the background attachment-property

The background-attachment property specifies whether the background image should scroll or be fixed (will not scroll with the rest of the page)

The background attachment of the image is set like this:

body {
  background-image: url("image.png");
  background-repeat: no-repeat;
  background-position: right top;
  background-attachment: fixed;//image will be fixed with the rest of the page
  background-attachment: scroll;//image will scroll with the rest of the page
}