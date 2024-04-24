# CSS Box Model: Rothko Painting

[Live Preview](https://raw.githack.com/codem1ner/free-code-camp/main/responsive-web-design/box-model-rothko-painting/index.html)

# Rothko Painting Project

This project is a simple HTML and CSS project that replicates a Rothko painting. The painting is created using `div` elements and CSS properties.

## HTML Structure

The HTML structure is as follows:

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <link rel="stylesheet" href="styles.css">
  <title>Rothko Painting</title>
</head>
  <body>
    <div class="frame">
      <div class="canvas">
        <div class="rectangle-one"></div> 
        <div class="rectangle-two"></div>
        <div class="rectangle-three"></div>
      </div>
    </div>
  </body>
</html>
```

The `<div>` elements are used to create the different parts of the painting. The outermost `<div>` with the class `frame` acts as the frame of the painting. Inside the frame, there's another `<div>` with the class `canvas` which acts as the canvas of the painting. Inside the canvas, there are three more `<div>` elements, each representing a rectangle in the painting.

## CSS Styles

The CSS styles are used to style the `div` elements to look like a Rothko painting. Breakdown of the CSS:

### .canvas

```css
.canvas {
  width: 500px;
  height: 600px;
  background-color: #4d0f00;
  overflow: hidden;
  filter: blur(2px);
}
```

The `.canvas` class styles the canvas of the painting. The `width` and `height` properties set the size of the canvas. The `background-color` property sets the background color of the canvas. The `overflow: hidden;` property ensures that nothing spills out of the canvas. The `filter: blur(2px);` property applies a blur effect to the canvas, giving the painting a soft look.

### .frame

```css
.frame {
  border: solid black 50px;
  width: 500px;
  padding: 50px;
  margin: 20px auto;
}
```

The `.frame` class styles the frame of the painting. The `border: solid black 50px;` property creates a solid black border around the frame. The `width` property sets the width of the frame. The `padding: 50px;` property creates space between the frame and the canvas. The `margin: 20px auto;` property moves the frame down 20px and centers it horizontally.

### .rectangle-one, .rectangle-two, .rectangle-three

```css
.rectangle-one {
  width: 425px;
  height: 150px;
  background-color: #efb762;
  margin: 20px auto;
  box-shadow: 0 0 3px 3px #efb762;
  border-radius: 9px;
  transform: rotate(-0.6deg);
}

.rectangle-two {
  width: 475px;
  height: 200px;
  background-color: #8f0401;
  margin: 0 auto 20px;
  box-shadow: 0 0 3px 3px #8f0401;
  border-radius: 8px 9px;
  transform: rotate(0.4deg);
}

.rectangle-three {
  width: 91%;
  height: 28%;
  background-color: #b20403;
  margin: auto;
  filter: blur(2px);
  box-shadow: 0 0 5px 5px #b20403;
  border-radius: 30px 25px 60px 12px;
  transform: rotate(-0.2deg);
}
```

The `.rectangle-one`, `.rectangle-two`, and `.rectangle-three` classes style the three rectangles in the painting. The `width` and `height` properties set the size of the rectangles. The `background-color` property sets the color of the rectangles. The `margin` property centers the rectangles and creates space between them. The `box-shadow` property creates a shadow effect around the rectangles. The `border-radius` property rounds the corners of the rectangles. The `transform: rotate();` property rotates the rectangles to give the painting an imperfect, hand-painted look.

### .rectangle-one, .rectangle-two

```css
.rectangle-one, .rectangle-two {
  filter: blur(1px);
}
```

The `.rectangle-one, .rectangle-two` selector applies a blur effect to the first and second rectangles, giving them a soft look.
