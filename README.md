# CSS Layout Assignment

In this assignment, you will practice the concepts covered in the CSS Layout lecture. You will be creating and modifying an HTML page and applying CSS styles to achieve specific layout goals.

## Task 1: Display and Position

1. Create an HTML file with the following structure:

```html
<!DOCTYPE html>
<html>
<head>
    <link rel="stylesheet" type="text/css" href="styles.css">
</head>
<body>
    <div class="container">
        <div class="box">Box 1</div>
        <div class="box">Box 2</div>
        <div class="box">Box 3</div>
        <div class="box">Box 4</div>
        <div class="box">Box 5</div>
    </div>
</body>
</html>
```

2. Create an external CSS file (styles.css) and apply the following styles:

- Set the default display of the `.box` elements to `inline-block`.
- Add a border to the `.box` elements with a width of 2px, a solid black color, and a margin of 10px.
- Set the height and width of the `.box` elements to 100px.
- Set the font-size of the `.box` elements to 18px.
- Add some padding to the `.box` elements.

3. Open the HTML file in a web browser and observe how the boxes are displayed in multiple rows. Ensure that the elements are inline-block and have the specified dimensions and spacing.

## Task 2: Understanding Box Sizing

1. Modify the styles in your CSS file to include the following:

- Apply `box-sizing: border-box` to all elements (`*`) on the page.

2. Test this change by adjusting the padding and border of one of the `.box` elements using the browser's inspector. Observe how the element's content adjusts dynamically without affecting the layout.

## Task 3: Eliminating Extra Space

1. Add a container `<div>` with the class `.container` around the `.box` elements in your HTML.

2. Update your CSS file to include the following styles:

- Set the font-size of the `.container` to 0.
- Set the font-size of the `.box` elements inside the container to 18px (or any desired size).

3. Observe how the extra space between the `.box` elements is removed, and the boxes are now neatly aligned.

## Task 4: Clearing Floats

1. Add the following HTML code after the `.container` div:

```html
<div class="clear-box">
    <div class="float-box">Floating Box</div>
    <div class="text">This is some text that should not overlap the floating box.</div>
</div>
```

2. In your CSS file, add styles to achieve the following:

- Float the `.float-box` to the left.
- Apply a `clear` property to the `.text` class to clear the float on the left side.

3. Test the styles by viewing the HTML in your browser. Make sure that the text does not overlap the floating box.

## Task 5: Handling Overflow

1. Create a new section in your HTML with a container div and several boxes inside, similar to the previous tasks.

2. Set a fixed height for the container, such as 300px, and ensure that there are more boxes than can fit within the container.

3. In your CSS file, apply the `overflow: hidden` property to the container.

4. Observe how the overflowing content becomes hidden. You can also experiment with `overflow: scroll` and `overflow: auto` to see the differences in behavior.

## Task 6: Pseudo and Dynamic Classes

1. Create a new HTML file and add some hyperlinks (`<a>`) and input elements (`<input>`) to it.

2. In your CSS file, apply styles to the following pseudo-classes:

- `:link`: Set the color of unvisited links to green.
- `:visited`: Set the color of visited links to yellow.
- `:hover`: Change the color and background color of links when hovered over by the cursor.
- `:focus`: Change the color of input elements when they are in focus.
- `:checked`: Change the height and width of checked input elements.
- `:valid`: Change the color of input elements with valid content.
- `:invalid`: Change the color of input elements with invalid content.

3. Test these styles by clicking on links and interacting with input elements.

## Task 7: Z-Index

1. Create a new HTML file with two or more elements that overlap.

2. Apply the `z-index` property to these elements in your CSS file. Experiment with different `z-index` values to control their stacking order.

3. Observe how elements with higher `z-index` values appear on top of elements with lower values.

---

Once you have completed these tasks, you will have a better understanding of CSS layout properties, and how to use them to control the layout and appearance of elements on a web page.
