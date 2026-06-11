# Exercise-5
## Predict the Output
### Scenario A
 #### - What color is the text?
 Red

#### - Is it underlined?
yes

#### - Is it aligned left, center, or right?
It is aligned at the center
#### - Explain the logic behind your three answers.
- the color is red because inline css overrides external css due to its ability to directly target the element
- The text is underlined because the external css style is applied
- It is center aligned because inline css overrides external css due to its ability to directly target the element


### Scenario B
#### Are #333333 and rgb(51, 51, 51) the same color? __________ Show your math/explanation.
- yes they are the same because the decimal form of `#333333` is (51, 51, 51) which is red, green, blue in rgb.
- 33 = (3 × 16) + 3 = 51
- 33 = (3 × 16) + 3 = 51
- 33 = (3 × 16) + 3 = 51

So `#333333` = `rgb(51, 51, 51)`, they are exactly the same color just written in two different formats.
#### If you remove the entire p rule, what font family will paragraphs use and why?
Poppins, sans-serif  because without the `p` rule, paragraphs no longer have their own `font-family`. They will inherit the `font-family` from the `body` rule, since `font-family` is an inherited property in CSS.

### Scenario C
#### What color does the `<h1>` end up?
- `color: hsl(240, 100%, 50%)` which is blue.
#### Why doesn't the first rule apply?
- The first rule does not apply since both rules have the same selector and same specificity, because of the the cascade effect which is also known as the waterfall effect which is from top to bottom, so the bottom property applies to the stylesheet because of the cascade effect.
#### What CSS principle does this demonstrate?
The cascade, specifically the source order rule. When two rules have the same selector and specificity, the one that appears last in the stylesheet always wins.