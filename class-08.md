# More CSS Layout
CSS treats each HTML element as if it is in its own box. This box will either be block-level box or inline-box. `img`, `b` and `i` tags will automatically be inline-block while `h1`, `p`, `ul`, and `li` will be block. Block-level boxes will start on a new line and act as the main building blocks of any layout, while inline boxes flow between surrounding text. They can be controlled on how much space each box takes up by setting the width of the boxes. To seperate boxes, you can use borders, margins, padding and background colors. Containing elements, if one block-level elemt sits inside another block-level element the the outer box is known as the parent element. When calling a section of HTML to customimize, this is refered to as the selector. CSS has the following postioning schemes that allow the layout of the page:
- Normal flow 
- Relative 
- Absolute 
- Fixed
- Floating elements
When you move any elemt from normal flow, boxes can overlap. The `z-index` property allows you to control which box appears on top.  