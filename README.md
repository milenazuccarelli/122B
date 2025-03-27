# 122B

A website that weighs 122 bytes. It's has minimal styling, i.e. black background and white text only to show that there is some amount styling. Vertically and horizontally centered because that remains one of the biggest hassles for devs to work out with css.

## Description

This is how I did it:
* skipped the `<html>`, `<head>` and `<body>` tags
* used the css wildcard `*` for styling to save chars
* used the shorthand 3-digit HEX value for background and font and ommitted the `#` for white as it's not needed
* used `height:1` without specifying a unit (for vertical sizing) 
* used the shorthand property `inset: 0`: read more [here](https://developer.mozilla.org/en-US/docs/Web/CSS/inset) 
* no spaces and no indentation for maximum compression
* the last CSS property doesn't require a semicolon, nor does it require a closing bracket `}`
* omitted the closing `</style>` tag, most browsers will close this automatically

24 bytes are owed to the text on the screen that reads "this page weighs 122 bytes". 
98 bytes or the HTML (I use this term lightly) and CSS.

In UTF-8 encoding, ASCII characters each take up 1 byte, which makes the counting straightforward in this case. This markdown files weighs 1257 bytes (just over a kilobyte).