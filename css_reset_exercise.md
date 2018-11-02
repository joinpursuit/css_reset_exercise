# CSS Reset

Inside this folder, you'll find an HTML file called `index.html`. It should look pretty similar to the other HTML files you've worked with. There's only one problem: _there isn't any CSS file_.

Your boss doesn't want you to write exact CSS yet, but their design team has a few basic ideas for what they want it to be. These ideas are as follows:

- All text should be _sans-serif_. Most default text rendering in browsers (without an explicit CSS file) renders text in _serif_ font.
- All `p` tags should have 20 pixels of padding on the top and the bottom - _not_ on the sides.
- All images should be 200 pixels tall.
- Header tags (`h1`, `h2`, etc.) should be closer in size to each other. Management would like `h1` to have a 25px font size and all other `h` tags to have a 20px font size.
- Lists should have 30px of padding on the left.
- The `background-color` of the entire `body` should be `limegreen`. CSS should understand what that means.

Beyond these settings, the design team wants **no default styling** whatsoever.

## Getting Started

- Create a css file called `index.css`. In the `head` tag of your HTML file, write the following:

```html
<link rel="stylesheet" href="./index.css">
```

- In your `index.css` file, copy and paste the CSS Reset material from today's lecture. Observe how the style of the page changes. This is because we are cancelling out the default styling of our web browsers. Chrome and Firefox want to help us out if we don't have styling ourselves - but sometimes, they just get in the way.

- Underneath your CSS reset code, add references to each tag the design team wants you to update. Note that **when you add your tags underneath** the reset, the bottom tags supersede the reset commands in importance.
  - The following CSS attributes will be important:
    - `padding`
    - `font-family`
    - `font-size`
    - `background-color`


*// //*

https://www.w3schools.com/css/css_list.asp

running scared man transparent icon

./assets/closeUpMan.png, https://rpelm.com/images/scooby-doo-clipart-19.png
