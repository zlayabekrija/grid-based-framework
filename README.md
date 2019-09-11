
#The FrAmE framework

  

> Full fledged grid based framework no JS, just simple CSS .

  

In order to solve the issues of robust CSS frameworks with many dependencies, our focus was on creating the framework for common basic CSS styling.

## Resets

Reset of all the css values is included in the framework

## Navbars

  

- common navbar with links placed vertically with classes for links or elements `v-nav-links` or `v-nav-items`

  

- navbar with horizontally placed links `h-navbar`

  

- responsive navbar needs to have the class of `md` in order to respond on screen size

  

- themed navbar with palette of 17 colors accomplished by adding the name of the color as an class (example `h-navbar navy`)

  

## Grid columns

  

> Bootstrap-like 12 column based pattern

  

**Each grid based system needs to have parent element of `row` class**

- columns sizes are in range from `col-1` for smallest (~8.3 %) to `col-12` that is 100% of the parent element

- since columns are arranged from left to right, column offset postion can be adjusted by applying the class `col-number-offset` to the class of column (example `col-1-offset` will move column to the right by ~8.33%). Range of offset is from 1 to 6.

  

## Forms

  

> Common type of forms with elements horizontally and vertically aligned

  

- each from starts with parent element of class of `form`

  

- themed form has additional class of `themed`

  

- inline forms (ex. search forms) are having `form-inline` as parent element

  

## Colors & Themes

  

There are 17 common types of colors and themes. Themes will change the color on hover.

  

- color needs to have named class of the color (ex. `maroon`)

  

- theme will be called in similar manner with appending the theme on class name (ex. `maroon-theme`)

  

#### The colors and themes :

  

![](https://placehold.it/15/ffffff/000000?text=+) `White`  &nbsp;  ![](https://placehold.it/15/000000/000000?text=+) `Black`  &nbsp;
![](https://placehold.it/15/dddddd/000000?text=+) `Silver`  &nbsp;![](https://placehold.it/15/ff0000/000000?text=+) `Red`  <br/>  ![](https://placehold.it/15/aaaaaa/000000?text=+) `Gray`  &nbsp;  ![](https://placehold.it/15/3d9970/000000?text=+) `Olive`  &nbsp;
![](https://placehold.it/15/ff851b/000000?text=+) `Orange`  &nbsp;![](https://placehold.it/15/39cccc/000000?text=+) `Teal`  <br/>![](https://placehold.it/15/b10dc9/000000?text=+) `Purple`  &nbsp;  ![](https://placehold.it/15/ffdc00/000000?text=+) `Yellow`  &nbsp;
![](https://placehold.it/15/7fdbff/000000?text=+) `Aqua`  &nbsp;![](https://placehold.it/15/f012be/000000?text=+) `Funchisa`  <br/>  ![](https://placehold.it/15/01ff70/000000?text=+) `Lime`  &nbsp;  ![](https://placehold.it/15/0000ff/000000?text=+) `Blue`  &nbsp;
![](https://placehold.it/15/b03060/000000?text=+) `Maroon`  &nbsp;  ![](https://placehold.it/15/000080/000000?text=+) `Navy`  &nbsp;  ![](https://placehold.it/15/00ff00/000000?text=+) `Green`

  
## Borders

Border classes will allow us to define border thikness and position (top,left...)

- `b-number` will make border around the element from all four sides (ex `b-1`) range of the widths is form 1 to 5
- `b-0` will remove border around the element

- `b-position-number` will place the boder on specific part of the element (ex `b-t-1` will make border top with 1 px width)

- possible postions are `top`,`bottom`,`left` and `right`.

## Padding

With padding classes we can set padding to the top,bottom,left and right

- `p-number` will set the padding around the element (ex. `p-1`). The range is from 1 to p

- `p-0` will set padding to zero

- `p-postiion-number` will add the padding to desired position (ex. `p-l-1`). Postions allowed are top,bottom,left and right.

 ## Margin

With margin classes we can set margin to the top,bottom,left and right

- `m-number` will creat the margin around the element (ex. `m-1`). The range is from 1 to p

- `m-0` will set margin to zero

- `m-postiion-number` will add the margin to desired position (ex. `m-l-1`). Postions allowed are top,bottom,left and right. 

## Utility classes


> Display properties

    Block - d-block or d-b
    Inline - d-inline or d-i
    Inline Block - d-inline-block or d-i
    Flex - d-flex or d-f
    None - d-one

> Float properties

    Float left - f-left
    Float right - f-right
    Clear float - clearfix

> Text properties

    Align left - left
    Align right - right
    Align center - center

> Flexbox properties

    Justify center - jc-flex-center
    Justify start - jc-flex-start
    Justify end - jc-flex-end
    Justify space around - jc-space-around
    Justify space between - jc-space-between

> Flex direction properties

    Flex directon row - fd-row
    Flex direction column - fd-col
    Flex wrap - f-wrap
    Flex no wrap - f-nowrap
    Flex grow - f-grow-[1 or 0]
    Flex shrink - f-shrink-[1 or 0]

> Border radius properties

    Border radius - br-[1 to 5]
    Border round - b-round



This project is the collaboration of [Zlatan](https://github.com/zlayabekrija) & [Inzi](https://github.com/inhaq). [Preview this project](https://zlayabekrija.github.io/grid-based-framework/)


