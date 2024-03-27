# Basic HTML Project: Half Moon and Stars

This project creates a simple visual representation of a half moon with stars in the night sky using basic HTML and CSS.

## HTML Structure:

- `<!DOCTYPE html>`: Specifies the document type and version of HTML.
- `<html lang="en">`: Defines the document as HTML with English as the primary language.
- `<head>`: Contains meta-information about the HTML document such as character set and viewport settings.
- `<meta charset="UTF-8">`: Sets the character encoding to UTF-8.
- `<meta name="viewport" content="width=device-width, initial-scale=1.0">`: Sets the viewport to the width of the device and initial scale to 1.0 for responsive design.
- `<style>`: Contains CSS styling for the document.
- `<body>`: Represents the content of the HTML document.

## CSS Styling:

- `.half-moon`: Defines a circular shape representing the moon using CSS properties like width, height, background color, border-radius, and positioning.
- `.moon-cut`: Represents the cut portion of the moon using CSS transformations like scale and rotate.
- `.star`, `.star1`, `.star2`, `.star3`, `.star4`, `.star5`: Defines star shapes using CSS properties like position, width, height, background color, and clip-path. Each star is positioned at different coordinates on the page.

## Description:

- The background of the page is set to black to represent the night sky (`body` CSS).
- A half-moon shape is created using a circular div (`div.half-moon`) with a gray color and a cutout portion to mimic the phases of the moon (`div.moon-cut`).
- Stars are represented as white polygons (`div.star`, `div.star1`, ..., `div.star5`) using CSS clip-path property.
- Each star is positioned at different coordinates on the page using the `top` and `left` properties.

## Output:

- When viewed in a web browser, the HTML document will display a half-moon with stars scattered across the night sky against a black background.

This project demonstrates basic HTML and CSS skills for creating simple visual elements on a webpage.
