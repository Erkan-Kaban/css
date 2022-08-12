# CSS

## Box Model

- consists of a margin edge, border edge, padding edge, content edge, content width, content height.

## box-sizing
- **content-box** 
- `box-sizing: content-box`

gives you the **default** CSS box-sizing behaviour. For example if you set the width to 100 px the elements content will will be 100 wide and the width of any border or padding will be added to the final width, **making it wider than 100 px**

- **border-box**
- `box-sizing: border-box`
- border-box when set, your width and height that are set totals the sizing of your box, if your width is 100 pixels and height is 100, the content box will shrink to absorb that extra width.

## inline and block elements

- inline are elements that will shape themselves inline and only take up as much horizontal space as its required by the content.

- block elements takes up horizontal space as its content, and it always starts on a new line.

## Display Property

- You can change block elements into inline by using `display: inline-block` 


## Overflow

- if the content is larger than the size of the elment it will overflow, the default value of the overflow property is **visible** and will show a scroll bar in its place.

## Pseudo-classes

- button:hover < the colon with hover is the pseudo class. it gets added to the selector. 


## Absolute units and Relative Units

- Aboslute units: are exact units like cm, mm, px. The best unit out of the lot is px but is strongly discouraged.

- Relative units: are units that relate to the html document, rem is the default sizing used in the html, so a rem 2 would be two times the default sizing, em is related to its parent element like for example the size lettering of a h1.
  - % relative to the size of the parent element.
  - VH is the viewport heigh eg takes up the entire screen of whatever device it is viewed on.
  - VW - relative to the width of the viewport
  - EM - relative to the font size of the parent
  - is related to the root 


## Positioning

- Static: The element is in the normal flow of the document, this is the default value.

- relative: relative to the elements normal position.

- absolute: relative to the first parent whos position is set.

- fixed: relative to the viewport.

- sticky: relative to the nearest scrolling ancestor.

## Inheritance

- inheritance controls what happens when no value is specified for a property on an element.

- inherited properties are set to a  value manually.

- non-inherited by default

- color: initial, sets the color so it doesn't inherit its parent element.

- border by default is not inherited, but if border is set to inherit, it inherits