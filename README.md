# CSS Reference
---

To see different templates, checkout the respective branch. Below are the list of css branches with there description.

## Nat-ours

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
````
<div class="feature-box">
    <i class="feature-box__icon icon-basic-heart"></i>
    <h3 class="heading-tertiary">LIVE a healthier life</h3>
    <p class="feature-box__text">
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Asperiores nulla deserunt
    </p>
</div>
````
* More complex elements - popups, checkboxes etc