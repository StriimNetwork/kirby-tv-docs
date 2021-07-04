# Basic Information

## Files

The entirety of the Kirby TV Channel is coded in ActionScript. The `00000001.app` file, which is the dol loader is basically a Flash Player, modified to expose the Wii's API. 

## XML Structure

Every XML in the channel must follow this structure:

```markup
<?xml version="1.0" encoding="utf-8" ?>
<data version="1.0" code="HCMP">
</data>
```

`code` must equal the value of `GAME_CODE` in the `ApplicationController.as` file found at `trusted` in `00000002.app.`

```javascript
static var GAME_CODE = "HCMP";
```



