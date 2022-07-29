# jQuery

*Learning jQuery*

- `document.querySelector("h1")` <=> `document.querySelectorAll("button")` <=> `jQuery("h1")` <=> `$("h1")`
- Either put jQuery CDN script and JS script before `</body>` OR put them in `<head>` and add all JS script inside `$(document).ready(function(){//all JS code});`
- JS and CSS minifier (https://www.minifier.org/) [Reduces file size by removing comments, whitespaces and enhances load rate]
- `.css("color", "blue")`, `.css("font-size")` (not recommended to manipulate styles in JS)
- `.addClass("title margin-50")` (use this function to add .title which contains CSS) (Separating our concerns)
- `.removeClass("title")`
- `.hasClass("margin-50")` [returns true/false]
- **Manipulating text:** `.text("Bye")` [instead of .textContent], `.html("<em>Hey</em>")` [instead of .innerHTML]
- `.attr("src")` [getting the attribute]
- `.attr("src", "https://www.google.com")` [setting the attribute]
- **Event listeners:** `.click(function(){//code});` [it will add click event listener to all elements before the dot] [click, keypress, keydown, etc]
- `.on("<event>", function(){})` [similar to `.addEventListener()` in vanilla JS]
- **Add/Remove elements:** `.before(<HTML element>)`, `.after(<HTML element>)`, `.prepend(<HTML element>)` [adds inside selected element before its content], `.append(<HTML element>)` [adds inside selected element after its content]
- `$("button").remove();` [will remove all button elements]
- **Animations:** `.hide()`, `.show()`, `.toggle()`, `.fadeOut()`, `.fadeIn()`, `.fadeToggle()` [all these methods have toggle options], `.slideUp()`, `.slideDown()`, `.slideToggle()`, `.animate({opacity: 0.5})` [only numeric CSS properties allowed]
