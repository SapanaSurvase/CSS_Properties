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

##Demonstration
Index page:
![index](https://user-images.githubusercontent.com/88648906/130120907-ba3115c3-e882-4fbf-8ef8-017d8969f8eb.PNG)

Background Properties:
![background](https://user-images.githubusercontent.com/88648906/130121095-0433de65-d557-4e90-ba9d-9dcd98a5c4ed.PNG)
![bg_picture](https://user-images.githubusercontent.com/88648906/130121120-71cf3514-7866-4728-a3d9-7007d60ac9c3.PNG)

Border Properties:
![border1](https://user-images.githubusercontent.com/88648906/130121188-8dfc36bc-6fb5-4b77-b247-09f67efb1721.PNG)
![border2](https://user-images.githubusercontent.com/88648906/130121223-bdd8acb1-2b25-4a22-b038-a62ebefb2bc2.PNG)

BOX Properties:
![box_prop1](https://user-images.githubusercontent.com/88648906/130121365-b70526bf-f01b-46b7-a6c6-c47f8811635b.PNG)
![box_prop2](https://user-images.githubusercontent.com/88648906/130121397-808c1196-e5f9-4346-b00b-db78f4910616.PNG)

Filter Property:
![filter](https://user-images.githubusercontent.com/88648906/130121476-797601f0-dc85-4f2c-8e10-623f1aa14e1d.PNG)

Clipping and masking properties:
![clipping_masking](https://user-images.githubusercontent.com/88648906/130121637-3bfec3cc-3c90-4a38-a60a-635f2372b0a3.PNG)

Positoining Properties:
![positioning](https://user-images.githubusercontent.com/88648906/130121724-248881e9-6c96-4670-aa21-abc071896b63.PNG)

flex property:
![flex1](https://user-images.githubusercontent.com/88648906/130121798-a9c9df76-a039-4618-bb6d-7d531f2ccd8b.PNG)
![flex2](https://user-images.githubusercontent.com/88648906/130121837-eb68730d-1922-4af7-81e8-05eaf350c52d.PNG)

Text Properties:
![text](https://user-images.githubusercontent.com/88648906/130121872-8a263714-e0eb-4088-9314-8f6d4616af8f.PNG)

transition property:

Z-Index property:
![z-index](https://user-images.githubusercontent.com/88648906/130122020-389ccd82-efef-40ec-bba3-754b1651aac4.PNG)

