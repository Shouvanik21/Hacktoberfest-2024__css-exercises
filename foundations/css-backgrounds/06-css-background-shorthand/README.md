# Adding CSS Background shorthand property
In this exercise, you're going to practice using the background shorthand-property

To shorten the code, it is also possible to specify all the background properties in one single property. This is called a shorthand property.

Instead of writing:

body {
  background-color: green;
  background-image: url("image.png");
  background-repeat: no-repeat;
  background-position: right top;
}

You can use the shorthand property background like this:

body {
  background: green url("image.png") no-repeat right top;
}