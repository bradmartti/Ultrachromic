# Ultrachromic
The final form, the true evolution of the chromic theme saga!

To use this theme, it is recommended you simply use the Skin Manager Plugin https://github.com/danieladov/jellyfin-plugin-skin-manager, once installed select the Ultrachromic theme, make any changes you want, and apply it.

Alternatively, use one of the presets, but this will not allow for as much customization.

Ultrachromic can also be fully utilized without the plugin, but doing so involves building your theme manually using various import lines, doing it this way isn't very user friendly. Below is a step by step.

## Import lines

To use the theme copy paste the lines below to "Dashboard>General>Custom CSS" and click save, it will apply immediately server-wide to all users on top of any theme they may be using. To remove the theme, clear the "Custom CSS" field and then click save. **NOTE: Theme may not work when using reverse proxy**, check the bottom section of this readme for more info.

Ultrachromic is composed of multiple "parts" allowing you to theme only the parts you want, and to have some choice in how you want things themed.

### Required

This line is required.

```css
@import url('https://ctalvio.github.io/Ultrachromic/base.css');
```


### Recommended

```css
@import url('https://ctalvio.github.io/Ultrachromic/fixes.css');
@import url('https://ctalvio.github.io/Ultrachromic/jf_font.css');
```

### Choose style

