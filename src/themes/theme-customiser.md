# Theme Customiser

## Basic Options (No Code)
The theme customiser is a basic part of WordPress that has been modified to include options primarily relating to base colours.

To access the theme customiser, in the WordPress dashboard, go to `Swwwift > Theme Customiser` which will take you directly to the theme customiser panel.

From here, you'll be presented with options for base button styles, typography styles and basic page styles which you are free to select.

## Advanced Options (CSS Editor)
You can also find a CSS editor in the customiser by going to the WordPress dashboard and selecting `Swwwift > Theme CSS`.

::: danger
There are limitations set on the CSS editor for security reasons. See below for a list of limitations.
:::

### CSS Editor Limitations
The following CSS properties have been disabled and when saved, will be stripped from the output.

```
@import '';

.stripped {
  background
  background-image
  border:
  border-image:
}
```

When you change the theme customisations, a root stylesheet will be automatically created and included in the front and backend to ensure your block editor and frontend match.