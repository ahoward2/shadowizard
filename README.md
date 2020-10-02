# What is this?

Get perfect shadows every time for the non-designer.

# Installation 

`npm i shadowizardjs --save`

Then...

```
import {shadowizard} from 'shadowizardjs';

shadowizard({
    shadow_type: 'soft',
    padding: true,
})
```

## Options

shadowizard supports 2 options, both of which are optional:

* *shadow_type* - _hard / soft_ (Defaults to soft)
* *padding* - _boolean_ (Defaults to false)