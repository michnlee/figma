Figma Masterclass 2023 | Figma Tutorial for Beginners by Mizko https://www.youtube.com/watch?v=XiqitRY3swo

# Assets

## PNGs, SVGs, JPGs

These assets can be copied and pasted directly into the Figma file.

## Naming Elements

Elements are automatically given a name when they are created however, we can rename them.

When renaming elements we can tell Figma what kind of element is it and then then assign it a value eg

```
Button / Primary will let Figma know that the element is a button and the value is primary
```

## Responsive Elements

We can make the auto layout elements responsive by using the Constraints section in the Design panel and selecting the desired constraint options. The elements then become constrained to the parent frame.

## Resizing Elements

Elements can be resized either by

1. Using the second section under the Design panel by either

   - Targeting the height and width individually, or
   - As one using the Constrain Proportions property (appears as a link icon).
     NB we can carry out math in the text boxes under this section eg if we type 342/2 in the width text box and press enter Figma will calculate it to be 171.

2. Using the mouse either
   - alone,
   - with shift to constrain its proportions, or
   - with shift and option to constrain its proportions and align it to the center.

# Style

To have quick access to pre-styled reusuable fonts and colors we can turn them into a style, and if/when these styles are updated they will also update all elements using said styles automatically.

## Fonts

1. Select the font family, size, weight and any other styles needed
2. Click on the Style Icon
3. Click the + button
4. Give the style a name
5. Click on Create Style

## Colors

1. Under Fill or Stroke select the color or colors (depending on the style eg solid, linear, etc) and the opacity and other stroke styles needed
2. Click on the Style Icon
3. Click the + button
4. Give the style a name
5. Click on Create Style

# Components

A component is a reusable asset that can be utilised throughout all designs.

The main component will have a symbol of four small squares and any instances/uses of the component will have an outlined diamond.

If the main component is edited, all instances of that component will also change. This allows you to save time by not having to individually edit each element.

## Component Sets

When a component set is created we can rename the component property under Property in the Design panel by selecting the componenet then pressing edit.

The varients of the component will also appear under the Properties set and can be selected when needed.

# Creating a project

To create a project we can press F to create a new frame and then select the type of frame or frame size from the options under the Design panel. we can also create a custom frame size by clicking on an empty area and dragging the mouse to the desired size.

# Auto Layout

Using auto layout allows us edit the layout of a group of elements eg the direction, alignment, spacing between each element and the vertical and horizontal padding.

We can also re-order the items in an auto layout by selecting the desired element and using the arrow keys to toggle where to place the item.

Use the three dots to access the Advanced Auto Layout Settings to further edit the grouped elements.

# Layout Grid

To assist with layout accuracy we can use a grid layout to the frame.

1. Under Layout Grid press the + icon,
2. Select the layout option in the drop down menu, for this we use columns,
3. Edit the options as needed.

# Prototyping

## Scroll Behavior of An Element

We can apply scroll behaviour to an element in the Prototype section of the panel on the right hand side under Scroll Behaviour and selecting the options provided.

### Fixed Navigation Bar

To create a fixed Navigation Bar, after selecting the element we can either

1. Under Constraints select the Fix position when scrolling option, or
2. Under the Prototype section in the panel on the right hand side under Scroll Behaviour, change the Poisiton to Fixed.

## Recreating the scroll effect

When creating a frame we can select clip content to clip anything sitting outside the frame.

To create the scroll effect in the video, we can do the following:

1. Double the size of the main frame and replace the background image with the second image.
2. Hide the second section by decreasing the height of the parent frame.
3. Duplicate the parent frame.
4. Select both sections and hold down shift and drag the items until the next frame appears.
5. Under prototype we then connect the first page frame to the second and vice-versa and select the "On CLick" interaction, then animate it as necessary.

# Shortcuts

1. Use Command to directly select an element even if it is nested.
2. Use Shift + A to apply auto layout to elements.
3. Use Command + D or Option + drag the mouse to duplicate and position elements.
4. Use Shift + i to open all components, plugins and widgets.
5. Use F to create a new frame.
6. Hold down Option while hovering to use the measuring tool.
7. Use Shift + G to toggle the grid layout off and on.
8. Use Command + Option + G to create a Frame around a selection of elements.
9. Use COmmand + D to duplicate an item.
