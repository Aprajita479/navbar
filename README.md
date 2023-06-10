# NAVBAR README

This is a simple HTML and CSS code snippet that creates a navigation bar (navbar) with a sidebar. The navbar is fixed on the left side of the screen and can be toggled to slide in and out of view.

## Usage

To use this code snippet, follow these steps:

1. Copy the HTML code into your HTML file.
2. Ensure you have the necessary CSS styles defined.
3. Customize the code as needed.

## HTML Structure

The HTML structure of the code is as follows:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>NAVBAR</title>
    <!-- CSS styles -->
</head>
<body>
    <div id="sidebar">
        <div class="toggle-btn" onclick="togglesidebar()">
            <!-- Toggle button -->
        </div>
        <ul>
            <li>Navigation Item 1</li>
            <li>Navigation Item 2</li>
            <li>Navigation Item 3</li>
            <li>Navigation Item 4</li>
            <li>Navigation Item 5</li>
        </ul>
    </div>
</body>
</html>
```

## CSS Styling

The CSS styles define the appearance and behavior of the navbar. Here are some key styles used:

- `#sidebar`: This is the ID selector for the sidebar. It positions the sidebar on the left side of the screen and defines its width, height, background color, and transition properties.
- `#sidebar.active`: This class is added to the sidebar element when the toggle button is clicked, causing the sidebar to slide into view.
- `li i`: This selector defines the styles for the arrow icon (`<i>`) that appears next to each navigation item. It defines the initial position and transition properties.
- Other styles define general body styles, background color, and various positioning and transition properties.

## JavaScript Function

The JavaScript function `togglesidebar()` is responsible for toggling the sidebar's active state when the toggle button is clicked. It adds or removes the `active` class to the sidebar element, triggering the CSS transition and animation.

## Customization

Feel free to customize the code to suit your needs. You can modify the navigation items, add additional styles, or enhance the functionality using JavaScript.

Please note that this code snippet does not include any external dependencies or the required Montserrat font. Make sure you have the necessary resources linked in your HTML file if you want to use them.

Enjoy using the navbar in your web projects!
