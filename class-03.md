# HTML and CSS by Jon Duckett

## Chapter 3

< ol > ordered list, use < li > for each listed iteam

< ul > unordered list, use < li > as well

< dl > defintion list, use < dt > for the term being defines and < dd > for the definition

Nested lists; you can make nested lists with the < ul > and < li >

## Chapter 13

Box Dimensions; when you need to make your own dimensions for a box, use width and height.
When using these, use pixels, percentages or ems.

When you need to limit boxes you can use min-width and max-width, as well as min-height and max-height.

When content is overflowing you can use overflow: hidden, or overflow: scroll, (scroll is cooler).

Every box has three properties; border, margin and padding (p 307)

## Border

You can use the border-width property with thin, medium and thick or pixels. You can NOT use percentages with border-width.
To control individual size of borders use; border-top-width, border-right-width, border-left-width, border-bottom-wdith.

You can customize the border style using border-style: (style);. You can do dotted, soilid, dashed, ect... You can individually control the sides of border using
border-top-style, border-left-style, border-right-style, border-bottom-style.

Going above and beyond: you can customize each side of the border using; border-top-color, border-right-color, border-bottom-color, border-left-color.

You can use the border property and specify the width, style, and color of border in that order; border: 3px dotted #0088dd; (p 312).

## Padding

Padding is how much space should appear between content of an element and its border.
Usually you use pixels but it is possible to use percentages and ems.

## Margin

The margin controls the gap between boxes.

# JS and JQuery by Jon Duckett

## Chapter 4 (starting 162)

If else statements allow you to include a code block if user answers false.
-The difference between if and if else statements; **If** statements only runs statements if condition is true.
- **If else** staements runs a condtion depending on if true or false, and has seperate conditions.

switch statements; " A switch tsatement starts with a varaible called the swtich value. Each case indicates a possible value for this variable and the code
that should run if the varaible matches that value. " (p 164)

## Loops

-For loops; "if you need to run code a specific number of times, use for loop." (p 170)

-while loops are for when you dont know how many times a code should run ( as long as code is true)

-Do while loops: 
