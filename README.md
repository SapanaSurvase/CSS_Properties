# CSS_Properties
CSS is the language we use to style a Web page.

What is CSS?
CSS stands for Cascading Style Sheets
CSS describes how HTML elements are to be displayed on screen, paper, or in other media
CSS saves a lot of work. It can control the layout of multiple web pages all at once
External stylesheets are stored in CSS files

--Why Use CSS?
CSS is used to define styles for your web pages, including the design, layout and variations in display for different devices and screen sizes.


--CSS Selectors
CSS Syntax=selector{declaration : value}
CSS selectors are used to "find" (or select) the HTML elements you want to style.
We can divide CSS selectors into five categories:
      1> Simple selectors (select elements based on name, id, class)
      2> Combinator selectors (select elements based on a specific relationship between them)
      3> Pseudo-class selectors (select elements based on a certain state)
      4> Pseudo-elements selectors (select and style a part of an element)
      5> Attribute selectors (select elements based on an attribute or attribute value)

--CSS Backgrounds
The CSS background properties are used to add background effects for elements.

-The background color of a page is set like this:
body {
  background-color: lightblue;
}

--There are three ways of inserting a style sheet:
External CSS
Internal CSS
Inline CSS

--CSS border
The CSS border properties allow you to specify the style, width, and color of an element's border.
The border-style property specifies what kind of border to display.

The following values are allowed:

dotted - Defines a dotted border
dashed - Defines a dashed border
solid - Defines a solid border
double - Defines a double border
groove - Defines a 3D grooved border. The effect depends on the border-color value
ridge - Defines a 3D ridged border. The effect depends on the border-color value
inset - Defines a 3D inset border. The effect depends on the border-color value
outset - Defines a 3D outset border. The effect depends on the border-color value
none - Defines no border
hidden - Defines a hidden border

--Flex
The flex property is a shorthand property for:

flex-grow
flex-shrink
flex-basis
The flex property sets the flexible length on flexible items.

--Opacity
The opacity property sets the opacity level for an element.
The opacity-level describes the transparency-level, where 1 is not transparent at all, 0.5 is 50% see-through, and 0 is completely transparent.

--Transition
The transition-property property specifies the name of the CSS property the transition effect is for (the transition effect will start when the specified CSS property changes).
Tip: A transition effect could typically occur when a user hover over an element.
Note: Always specify the transition-duration property, otherwise the duration is 0, and the transition will have no effect.

--Z-Index
The z-index property specifies the stack order of an element.
An element with greater stack order is always in front of an element with a lower stack order.
Note: z-index only works on positioned elements (position: absolute, position: relative, position: fixed, or position: sticky) and flex items (elements that are direct children of display:flex elements).
Note: If two positioned elements overlap without a z-index specified, the element positioned last in the HTML code will be shown on top.
