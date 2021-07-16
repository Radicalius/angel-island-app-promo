# Angel Island App Promo

Promotional Embed For the Angel Island App

Preview: https://radicalius.github.io/angel-island-app-promo/preview.html

## Embed Code

```
<iframe id=angel-island-promo src="https://radicalius.github.io/angel-island-app-promo/" /> 
```

## Sizing

The recommended aspect ratio for this embed is around 19 x 6.

The embed will expand to fit its container's width.  It will scale its height to maintain a 19 x 6 aspect ratio.  It may be useful to set constraints on its dimensions. For example:

```
<style>
    #angel-island-promo {
        width: min($min-width, $max-width);
        height: min($min-width * 0.315, $max-width * 0.315);
        border: none;
    }
</style>

```
Where `max-width` and `min-width` are the desired maximum and minimum size of the component. Note that `$min-width` must be in units of [viewport width](https://www.sitepoint.com/css-viewport-units-quick-start/) and `$max-width` in an absolute unit, e.g. pixels, for this to work correctly.