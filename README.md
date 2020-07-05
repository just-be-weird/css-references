# CSS Reference
---

To see different templates, checkout the respective branch. Below are the list of css branches with there description.

## OmniFood

* Basics of SASS - variables
````
$color-white: #ffffff;
$color-black: #000000;
````
* Media queries using mixins
````
@mixin clearfix {
    &:after {
        clear: both;
        content: "";
        display: table;
    }
}
````
* Simple grid classes generated using calc function
````
.col-1-of-2 {
    width: calc((100% - #{$gutter-horizontal})/ 2);
}
````
* Use-case example for BEM notation