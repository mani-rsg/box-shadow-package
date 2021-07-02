# What is this?

Get perfect shadows every time for the non-designers

# Installation

`npm i add-box-shadow --save`

Add `"box-shadow-pkg"` as class name to the html elements that you wish to give a box shadow

Then...

```
import {addShadow} from "add-box-shadow";
addShadow({
    shadow_type: "soft",
    padding: false
})
```

## Options

add-box-shadow supports 2 options, both of which are optional:

* *shadow_type* - _hard | soft_ (Defaults to soft)
* *padding* - _boolean_ (Defaults to false)