# 122B

A website that weighs 122 bytes.
Styled just enough to prove it's styled, i.e. black background and white text, centered vertically and horizontally because centering in CSS is a cross we all bear.

## Description

How I did it:
* skipped the `<html>`, `<head>` and `<body>` tags
* used the css wildcard `*` for styling to save chars
* used the shorthand 3-digit HEX value for background and font and ommitted the `#` for white as it's not needed
* used `height:1` without specifying a unit (for vertical sizing) 
* used the shorthand property `inset: 0`: read more [here](https://developer.mozilla.org/en-US/docs/Web/CSS/inset) 
* no spaces and no indentation for maximum compression
* the last CSS property doesn't require a semicolon, nor does it require a closing bracket `}`
* omitted the closing `</style>` tag, most browsers will close this automatically

24 bytes are owed to the text on the screen that reads "this page weighs 122 bytes". 
98 bytes is the HTML (I use this term lightly) and CSS.

In UTF-8 encoding, ASCII characters each take up 1 byte, which makes the counting straightforward in this case. This markdown file weighs 1186 bytes (just over a kilobyte).