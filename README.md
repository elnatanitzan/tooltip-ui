# Tooltip UI
Pure CSS/SCSS Tooltip Library. easy to use, clean design &amp; No need for JS at all!
### Demo

![](/tooltip.gif)


### Installation

**Manually:**

Download `tooltip.css` from this repo and add it to your code. e.g.

```html
<link rel="stylesheet" href="style/tooltip.css">
```

Define a tooltip data-text to your element and let the style.
in the data-text content Write what you want to appear in the Tooltip.
in the span area Write some text When you go hove on it with the cursor, the Tooltip will show.

To change different text and background color to Tooltip you can simply set as follows:
```css
[data-text][data-text-top]::before {
         background: ...;
         color: ...;
     }
```     

```html
<div><span data-text="..." data-text-top>...</span></div>
```

### Tooltip data-text specific style:
```html
Top Center:
<div><span data-text="..." data-text-top>...</span></div>

Top Right:
<div><span data-text="..." data-text-top="right">...</span></div>

Top Left:
<div><span data-text="..." data-text-top="left">...</span></div>

Bottom Center:
<div><span data-text="..." data-text-bottom>...</span></div>

Bottom Right:
<div><span data-text="..." data-text-bottom="right">...</span></div>

Bottom Left:
<div><span data-text="..." data-text-bottom="left">...</span></div>

Right Center:
<div><span data-text="..." data-text-right>...</span></div>

Right Top:
<div><span data-text="..." data-text-right="top">...</span></div>

Right Bottom:
<div><span data-text="..." data-text-right="bottom">...</span></div>

Left Center:
<div><span data-text="..." data-text-left>...</span></div>

Left Top:
<div><span data-text="..." data-text-left="top">...</span></div>

Left Bottom:
<div><span data-text="..." data-text-left="bottom">...</span></div>

```

### Credit

Made with love by [Elnatan Nitzan](https://linkpad.bio/elnatanitzan)
