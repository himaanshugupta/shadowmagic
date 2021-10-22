# Shadowmagic

This will give you perfect shadow everytime for your images.

## Installation

Runn the following command to install.

```bash
  npm i shadowmagic --save
```
### How to use it

```javascript
  import {shadowmagic} from "shadowmagic";

  shadowmagic({
      shadow_type: 'soft',
      padding: false
  });
```

### Options

* *shadow_type* - _hard | soft_ (Defaults to soft)
* *padding* - _boolean_ (Defaults to false)