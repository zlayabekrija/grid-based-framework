
# The FrAmE framework

  

> Full fledged grid based framework no JS, just simple CSS .   [Preview](https://zlayabekrija.github.io/grid-based-framework/)

  

In order to solve the issues of robust CSS frameworks with many dependencies, our focus was on creating the framework for common basic CSS styling.

## Getting started

In order to use the framework, please add following line to the `<head>` HTML file:

```
 <link rel="stylesheet" type="text/css" href="https://cdn.jsdelivr.net/gh/zlayabekrija/grid-based-framework/frame.css">
```

## Resets

Reset of all the css values is included in the framework

## Navbars

  

- common navbar with links placed vertically with classes for links or elements `v-nav-links` or `v-nav-items`

  

- navbar with horizontally placed links `h-navbar`

  

- responsive navbar needs to have the class of `md` in order to respond on screen size

  

- themed navbar with palette of 17 colors accomplished by adding the name of the color as an class (example `h-navbar navy`)

  Working example can be found [here](https://zlayabekrija.github.io/grid-based-framework/#navbar) .

## Grid columns

  

> Bootstrap-like 12 column based pattern

  

**Each grid based system needs to have parent element of `row` class**

| Type | Class Name|Range|
 |:----:|:---------:|:---:|
|Column Size| `col-`|1-12|
|Column Offset|`col- -offset`|1-6|

Working example can be found [here](https://zlayabekrija.github.io/grid-based-framework/#grid) .
  

## Forms

  

> Common type of forms with elements horizontally and vertically aligned

  

- each from starts with parent element of class of `form`

  

- themed form has additional class of `themed`

  

- inline forms (ex. search forms) are having `form-inline` as parent element

  Working example can be found [here](https://zlayabekrija.github.io/grid-based-framework/#from) .

## Colors & Themes

  
There are 17 common types of colors and themes. Themes will change the color on hover.

#### The colors and themes :
| Type | Class Name|
 |:----:|:---------:|
|![](https://placehold.it/15/ffffff/000000?text=+) `White`|`white` or `white-theme`|
|![](https://placehold.it/15/000000/000000?text=+) `Black`|`black` or `black-theme`|
|![](https://placehold.it/15/dddddd/000000?text=+) `Silver`| `silver` or `silver-theme`|
|![](https://placehold.it/15/ff0000/000000?text=+) `Red`|`red` or `red-theme`|  
|![](https://placehold.it/15/aaaaaa/000000?text=+) `Gray`|`gray` or `gray-theme` 
|![](https://placehold.it/15/3d9970/000000?text=+) `Olive`|`olive` or `olive-theme`|
|![](https://placehold.it/15/ff851b/000000?text=+) `Orange`|`orange` or `orange-theme`|
|![](https://placehold.it/15/39cccc/000000?text=+) `Teal`|`teal` or `teal-theme`|
|![](https://placehold.it/15/b10dc9/000000?text=+) `Purple`|`purple` or `purple-theme`|
|![](https://placehold.it/15/ffdc00/000000?text=+) `Yellow`|`yellow` or `yellow-theme`|
|![](https://placehold.it/15/7fdbff/000000?text=+) `Aqua`|`aqua` or `aqua-theme`|
|![](https://placehold.it/15/f012be/000000?text=+) `Funchisa`|`funchisa` or `funchisa-theme`|
|![](https://placehold.it/15/01ff70/000000?text=+) `Lime`|`lime` or `lime-theme`|  
|![](https://placehold.it/15/0000ff/000000?text=+) `Blue`|`blue` or `blue-theme`|
|![](https://placehold.it/15/b03060/000000?text=+) `Maroon`|`maroon` or `maroon-theme`|
|![](https://placehold.it/15/000080/000000?text=+) `Navy`|`navy` or `navy-theme`|
|![](https://placehold.it/15/00ff00/000000?text=+) `Green`|`green` or `green-theme`|

Working example can be found [here](https://zlayabekrija.github.io/grid-based-framework/#colors) .
  
## Borders

Border classes will allow us to define border thikness and position (top,left...)

 | Type | Class Name|Range|
 |:----:|:---------:|:---:|
 |border|`b-`| 1-10|
 |no-border| `b-0`| n/a|
|border-position|`m- -`|[`l,r,t,b`][`1-10`]|

Working example can be found [here](https://zlayabekrija.github.io/grid-based-framework/#border) .

## Padding

With padding classes we can set padding to the top,bottom,left and right

 | Type | Class Name|Range|
 |:----:|:---------:|:---:|
 |padding|`p-`| 1-10|
 |no-padding| `p-0`| n/a|
|padding-position|`p- -`|[`l,r,t,b`][`1-10`]|

Working example can be found [here](https://zlayabekrija.github.io/grid-based-framework/#padding) .

 ## Margin

With margin classes we can set margin to the top,bottom,left and right
 | Type | Class Name|Range|
 |:----:|:---------:|:---:|
 |margin|`m-`| 1-10|
 |no-margin| `m-0`| n/a|
|margin-position|`m- -`|[`l,r,t,b`][`1-10`]|

Working example can be found [here](https://zlayabekrija.github.io/grid-based-framework/#margin) .

## Utility classes


> Display properties
   
   
 | Type | Class Name|
 |:----:|:---------:|
 | Block|`d-block` or `d-b`|
 |Inline|`d-inline` or `d-i`|
 |Inline Block|`d-inline-block` or `d-i`|
 |Flex | `d-flex` or `d-f`|
  |None | d-none|

> Float properties

 | Type | Class Name|
 |:----:|:---------:|
 |Float left| `f-left`|
 |Float right|`f-right`|
 |Clear float| `clearfix`|

> Text properties

 | Type | Class Name|
 |:----:|:---------:|    
 |Align left|` left`|
 |Align right|` right`|
 |Align center|` center`|

> Flexbox properties

 | Type | Class Name|
 |:----:|:---------:|
|Justify center|`jc-flex-center`|
|Justify start| ` jc-flex-start`|
|Justify end|`jc-flex-end`|
|Justify space around| `jc-space-around`|
|Justify space between|` jc-space-between`|

> Flex direction properties

 | Type | Class Name|
 |:----:|:---------:|
|Flex directon row|` fd-row`|
|Flex direction column|` fd-col`|
|Flex wrap|` f-wrap`|
|Flex no wrap|`f-nowrap`|
|Flex grow|`f-grow-`[1 or 0]|
|Flex shrink|`f-shrink`-[1 or 0]|

> Border radius properties

 | Type | Class Name|Range|
 |:----:|:---------:|:----:|
 |Border radius| `br-`| 1 - 5|
 |Border round| `b-round`| n/a |


## Authors

- [Zlatan](https://github.com/zlayabekrija) & [Inzi](https://github.com/inhaq).


