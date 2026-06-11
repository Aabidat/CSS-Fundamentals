# CSS Fundamentals - Exercise Set
This exercise set covers the core concepts of CSS including how to link stylesheets, apply text styling, work with color formats, and understand how the browser decides which styles to apply.

## Exercise 1 - CSS Method Showdown
In this exercise, I worked with all three CSS methods — inline, internal, and external — on the same paragraph to understand which one wins and why. I learned that inline styles have the highest priority, followed by internal styles, and then external stylesheets. I made the paragraph green by adding a single line to the external stylesheet, then explored how changing the internal style value affects the result.

## Exercise 2 - The Broken Stylesheet
I was given a broken HTML and CSS file with at least five errors and had to find and fix all of them. The errors included a wrong attribute name on the <link> tag, an incorrect Google Fonts rel value, a missing opening curly brace, missing semicolons, and incorrect RGB syntax. This exercise helped me understand how small syntax mistakes can break an entire stylesheet.

## Exercise 3 - Color Format Detective
I identified and matched four CSS color formats — RGB, Hex, HSL, and named colors — based on their descriptions. I also converted the color red into all four formats, explored the difference between `rgb()` and `rgba()`, and converted `#000000` and `#ffffff` to RGB to confirm they are black and white.

## Exercise 4 - Style a Press Release
I styled a provided press release HTML file using only an external press.css file — no inline or internal styles. I applied Google Fonts, used four different color formats across the stylesheet, and used `p:first-of-type` to add word spacing to only the first paragraph without touching the HTML. I also tested text-decoration: line-through on the dateline and removed it because it made the date look crossed out, which is inappropriate for a professional press release.

## Exercise 5 - Predict the Output
I predicted the visual result of three CSS scenarios before testing them in the browser. The scenarios covered inline vs. internal style conflicts, color format equivalence, and duplicate CSS rules with the same selector. This exercise helped me understand specificity, the cascade, and source order.

## Exercise 6 - Reconstruct from Scratch
I recreated a webpage from a written description alone with no starter code provided. I built both `coffee.html` and `coffee.cs`s from scratch, linked two Google Fonts separately, used HSL for the heading color, a named color for the subheading, RGB for paragraph text, and `p:last-of-type` to apply word spacing to only the second paragraph.

## Exercise 7 - Conceptual Deep Dive
I answered four written questions about the core ideas behind CSS. I explained why a website cannot be built with CSS alone, described a real scenario where inline CSS causes serious maintenance problems, predicted paragraph color based on specificity, and gave a practical reason why CSS offers four different color formats instead of one.

## Key Concepts Covered

- Inline, internal, and external CSS
- The cascade and specificity
- Google Fonts integration
- Color formats — Hex, RGB, HSL, and named colors
- Text styling properties
- CSS pseudo-class selectors `(p:first-of-type, p:last-of-type)`
- CSS syntax debugging
