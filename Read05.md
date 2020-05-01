You will learn here...

# What is **CSS** :
stylin languge that alows you to create rules that control the way that each elment will look like in browser after rendering, **It** depends basicly on **HTML** so you cant just have CSS without HTML page first, consisting of tow parts:
- ***A selector:*** witch mean the elment witch we should give it the ruls and must look like `p {` and there is many kinds of like:

     ![CAP](https://3madov-77.github.io/learning-journal/New%20folder/Capture-1a.PNG)
 
- ***A declaration:*** witch mean the rules section witch refrence to the first part and looks like: `the rule: the property;}`
so CSS declarations always sit inside curly brackets `{}` 

# How to write CSS :
so there is three esintals ways to write **CSS** :
## 1. The External Way:
when we write the whole css code in diferint file then link to it in the HTML code inside the tag `<link>`
## 2. The Internal Way:
when you write the **CSS** code inside the same HTML code ***Under*** the Tag `<style>`
## 3. The Inline Way:
when you write only the **CSS** rules in the same element line after attrbute `style="the rule name='the property'"`

# Selctors in CSS :
ther is alot of selectors i will mention them in table :

|   Selctor  |   meaning of   | how it looks |
| ---------- |:--------------:| ------------ |
|Universal Selector|Applies to all elements in the document| `* {}`|
|Type Selector|Matches element names|`h1, h2, h3 {}`|
|Cl ass Selector|Matches an element whose class attribute has a value that matches the one specified after the period (or full stop) symbol|`p.note {}`|
|ID Selector|Matches an element whose id attribute has a value that matches the one specified after the pound or hash symbol|`#introduction {}`|
|Child Selector|Matches an element that is a direct child of another|`li>a {}`|
|Descendant Selector|Matches an element that is a descendent of another specified element (not just a direct child of that element)|`p a {}`|
|Adjacent Sibling Selector|Matches an element that is the next sibling of another|`h1+p {}`|
|General Sibling Selector|Matches an element that is a sibling of another, although it does not have to be the directly preceding element|`h1~p {}`|
<br>
<hr>
<br>

# Colors :
there is many types of colors like:
1. ## Text colors:
and also there is three ways to specify colors to text :
#### - color names:
witch is the simplest one and it just mention the color name after `color:`

#### - rgb values : 
witch shortcut to (**RED** **GREEN** **BLUE**) and the values for each color start from 0 to 255 and looks like `rgb(22, 33, 44)`

#### - The hex codes :
witch is six digits only start with `#`, and evry color has one

2.  ## Background colors :
witch css spuort for each HTML element to had one, you have to secify the color you want or it will be defultly as white color..

3. ## Hue Colors :
Hue is near to the colloquial idea of color. Technically speaking however, a color can also have saturation and brightness as well as hue

4. ## Saturation colors :
Saturation refers to the amount of gray in a color, At maximum saturation, there would be no gray in the color. At minimum
saturation, the color would be mostly gray

5. ## Brightness colors :
Brightness (or "value") refers to how much black is in a color, At maximum brightness, there would be no black in the color At minimum brightness, the color would be very dark

6.  ## Contrast :
When picking foreground and background colors, it is important to ensure that there is enough contrast for the text to be legible
<br>

 ![cap](https://3madov-77.github.io/learning-journal/New%20folder/Capture1-1b.PNG)

<br>

When text is harder to read, low contrast between background and foreground colors in difernt worlds
<br>

 ![cap](https://3madov-77.github.io/learning-journal/New%20folder/Capture1-2b.PNG)

<br>

For long spans of text, reducing the contrast a little bit improves readability
<br>

 ![cap](https://3madov-77.github.io/learning-journal/New%20folder/Capture1-3b.PNG)

<br>

it is easier to read when there is higher contrast between background and foreground colors (some times you can use it If you want people to read a lot of text on your page)
<br>

7.  ## The Opacity :
witch is property lows you to specify the opacity of an element, and it should be number betwin 0.0 AND 1.0, it caled alpha value in some css attr like `rgb`

<br>
<hr>
<br>

[`Back To The Main Page`](https://3madov-77.github.io/learning-journal/)