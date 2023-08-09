# CSS Shorthand note

### A. Background
```css
/*  Background CSS detail properties */
background-color: #000;
background-image: url(images/bg.gif);
background-repeat: no-repeat;
background-position: left top;
```
```css
/* Background shorthand */
background: #000 url(images/bg.gif) no-repeat left top;
```

### B. Font
```css
/* Font CSS detail properties */
font-style: italic;
font-weight: bold;
font-size: 0.8em;
line-height: 1.2;
font-family: Arial, sans-serif;
```
```css
/* Font shorthand */
font:
  italic bold 0.8em/1.2 Arial,
  sans-serif;
```
### C. Border
```css
/* Border detail properties */
border-width: 1px;
border-style: solid;
border-color: #000;
```
```css
/* Border shorthand */
border: 1px solid #000;
```
### D. Margin
```css
/* Margin detail properties */
margin-top: 10px;
margin-right: 5px;
margin-bottom: 10px;
margin-left: 5px;
```
```css
/* Margin shorthand */
margin: 10px 5px 10px 5px;
```
```css
/* Margin detail properties */
margin-top: 10px;
margin-right: 5px;
margin-bottom: 10px;
margin-left: 5px;
```
```css
/* Margin shorthand */
margin: 10px 5px;
```
```css
/* Margin detail properties */
margin-top: 10px;
margin-right: 5px;
margin-bottom: 15px;
margin-left: 5px;
```
```css
/* Margin shorthand */
margin: 10px 5px 15px;
```
```css
/* Margin detail properties */
margin-top: 10px;
margin-right: 10px;
margin-bottom: 10px;
margin-left: 10px;
```
```css
/* Margin shorthand */
margin: 10px;
```
### E. Padding
```css
/* padding detail properties */
padding-top: 10px;
padding-right: 5px;
padding-bottom: 10px;
padding-left: 5px;
```
```css
/* padding shorthand */
padding: 10px 5px 10px 5px;
```
```css
/* padding detail properties */
padding-top: 10px;
padding-right: 5px;
padding-bottom: 10px;
padding-left: 5px;
```
```css
/* padding shorthand */
padding: 10px 5px;
```
```css
/* padding detail properties */
padding-top: 10px;
padding-right: 5px;
padding-bottom: 15px;
padding-left: 5px;
```
```css
/* padding shorthand */
padding: 10px 5px 15px;
```
```css
/* padding detail properties */
padding-top: 10px;
padding-right: 10px;
padding-bottom: 10px;
padding-left: 10px;
```
```css
/* padding shorthand */
padding: 10px;
```

### F. Position
```css
/* Position detail properties */
top: 0;
right: 20px;
bottom: 0;
left: 20px;
```
```css
/* Position shorthand */
inset: 0 20px 0 20px;
```

### G. Outline
```css
/* Outline detail properties */
outline-width: 1px;
outline-style: solid;
outline-color: #000;
```
```css
/* Outline shorthand */
outline: 1px solid #000;
```
### H. List
```css
/* List detail properties */
list-style-type: disc;
list-style-position: inside;
list-style-image: url(disc.png);
```
```css
/* List shorthand */
list-style: disc inside url(disc.png);
```
### I. Animation
```css
/* Animation detail properties */
animation-duration: 5s;
animation-name: example;
animation-delay: 2s;
animation-direction: alternate;
animation-fill-mode: normal;
animation-iteration-count: infinite;
animation-play-state: running;
animation-timing-function: ease-out;
```
```css
/* Animation shorthand */
animation: 5s example 2s alternate infinite ease-out;
```
### J. Transition
```css
/* Transition detail properties */
transition-property: background, color;
transition-duration: 1s;
transition-timing-function: ease-out;
transition-delay: 60ms;
```
```css
/* Transition shorthand */
transition: background-color 1s ease-out 60ms;
```
### K. Flex
```css
/* Gap detail properties */
flex-grow: 1;
flex-shrink: 1;
flex-basis: 1em;
```
```css
/* Flex shorthand */
flex: 1 1 1em;
```
### L. Gap
```css
/* Gap detail properties */
row-gap: 1em;
column-gap: 2em;
```
```css
/* Gap shorthand */
gap: 1em 2em;
```
```css
/* Gap detail properties */
row-gap: 10px;
column-gap: 10px;
```
```css
/* Gap shorthand */
gap: 10px;
```
### M. flexflow
```css
/* Flexflow detail properties */
flex-direction: column;
flex-wrap: wrap;
```
```css
/* Flexflow shorthand */
flex-flow: column wrap;
```

