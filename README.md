# CSS-Fundamentals
Fundamentals for Cascade Style Sheet

## CSS Style Selectors
```
* - styling on all elements
#id - styling for particular id
.class - styling for particular group of elements
```

```
tag  - for a particular element
tag1, tag2 - multiple elements
tag1 tag2 - all tag2 inside tag1
tag1 > tag2 - all tag2 child of tag1
tag1 + tag2 - all tag1,tag2 combo (tag2 being next element after tag1)
```

```
//pseudo class
:hover - hover effect
:last-child - last child of element
:first-child - first child of element
```

```
!important - deems important so it can be overwritten
```

## Sizes : {px, em, rem, %}
```
px - pixel size (std)
em - equally magnified to parent element or default size for that element
rem - equally magnified to root element i.e., html
% - size based on screen size
```

## Browser support prefixes:
```
-moz-	-ms-	-webkit-	-o-
```

## CSS Styling properties:-
- color : text color
- background-color
- text-align
- width: size
- height: size
- border : size type color;
- margin: {size, updown sides, top right bottom left} [margin-left -right -top -bottom]
- padding: {size, updown sides, top right bottom left} [padding-left -right -top -bottom]
- box-shadow: 4px 4px 4px #888888;
- box-sizing: {border-box, content-box]; 
- background-image: url(...)
- background-size: cover;
- list-style: none;
- display: {inline, block}
- cursor: pointer;
- text-decoration: {underline, line-through};
- text-transform: {uppercase, lowercase};
- line-height: size;
- font-style: italic
- font-weight: size
- font-size: size
- font-family: "Time New Roman, Georgia", family
- letter-spacing: size 
- text-shadow: x y blur color;
```
[text-shadow: 
3px 1px 0 white,
4px 2px 0 green,
5px 3px 0 red; ]
```
- font-variant: {small-caps, inherit}
- float: {left, right}; [use clear:both to avoid floating other contents]

### flexbox (flexboxfroggy to practise)
- display: flex;
- flex-wrap: wrap;
- justify-content: center

### animations
- img {transition: all 1s;}
- img:hover{transform: scale(1.1);}

### Online Tools and Refrences
* https://www.w3schools.com/css/
* https://css-tricks.com/almanac/
* https://www.paletton.com/
* https://fonts.google.com/
