![Gotham Theme](http://i.imgur.com/AwnUwx9.png)
> The night is darkest just before the dawn. And I promise you, the dawn is coming.

Gotham is a **very dark** Sublime Text 3 UI Theme. I attempted to make something that was inspired by my go to color scheme 'Gotham'. Enjoy!

##### A Sublime Text 3 UI Theme

Largely based on the incredible work done by [arvi](https://github.com/arvi/Agila-Theme) with the Agila Theme.

***
## Screenshots
You can customize the UI to your liking _(e.g camouflage workspace with the color scheme background, sidebar, tab, autocomplete, and scrollbar setup/color preferences)_ by referring to the **"[Settings](#settings)"** section of this documentation.

Screenshots below use font face: [Adobe Source Code Pro](https://github.com/adobe-fonts/source-code-pro)

####Gotham Theme
![Screenshot](http://i.imgur.com/xAqgz61.png)
![Screenshot](http://i.imgur.com/VLXf1q0.png)

---

### How to Install

##### *Chill* way- available very soon
via [Package Control](https://packagecontrol.io/), where Gotham is listed as *`Gotham Theme`*.

1. Open Command Palette using menu item *`Tools -> Command Palette...`*
2. Choose `Package Control: Install Package`
3. Find *`Gotham Theme`* and hit *`Enter`*

##### *Daring* way
via installing the theme manually.

1. [Download the latest release .zip](https://github.com/9sevendesign/Gotham-Theme/releases)
2. Unzip and rename folder to Gotham-Theme
3. Move *`Gotham-Theme`* folder inside the Packages directory (*`Preferences > Browse packages...`*)

---

### Activate theme normal way
via User Preferences file (*`Sublime Text -> Preferences -> Settings - User`*). After setting up,
don't forget to **restart Sublime Text Editor** for changes to take effect.

##### Default theme
#
```json
"theme": "Gotham.sublime-theme",
"color_scheme": "Packages/Gotham-Theme/Gotham.tmTheme",
```
Note: You can use active guide with these schemes by adding:
```json
"indent_guide_options":
[
    "draw_normal",
    "draw_active"
],
```

---

### Icons
The theme uses [zz File Icons](https://github.com/oivva/st-file-icons) package to display file icons. Please install the package and restart Sublime.

### Settings
I've made some UI parts customizable | icon colors, sidebar items, etc..

##### THEME OVERRIDE
overrides default theme sidebar, scrollbars and tab background based on theme scheme background
```json
"theme_gotham_camouflage": true,
```
overrides default theme sidebar and tab background only based on theme scheme background
```json
"theme_gotham_camouflage_semi": true,
```

##### SIDEBAR COMPACT TREE STRUCTURE - NO INDENTATION
#
```json
"theme_gotham_compact_sidebar": true,
```

##### SIDEBAR TREE SIZE (default: medium)
#
```json
"theme_gotham_sidebar_mini": true,
"theme_gotham_sidebar_xsmall": true,
"theme_gotham_sidebar_small": true,
"theme_gotham_sidebar_medium": true,
"theme_gotham_sidebar_large": true,
```

##### SIDEBAR HEADING (default: theme-based color)
#
```json
"theme_gotham_sidebar_heading_white": true,
"theme_gotham_sidebar_heading_gray": true,
"theme_gotham_sidebar_heading_cyan": true,
"theme_gotham_sidebar_heading_yellow": true,
"theme_gotham_sidebar_heading_desaturated": true,
```

##### SIDEBAR ENTRY/ITEM FONT SIZE (default: 13)
#
```json
"theme_gotham_sidebar_font_xsmall": true, //font-size: 11
"theme_gotham_sidebar_font_small": true, //font-size: 12
"theme_gotham_sidebar_font_big": true, //font-size: 14
```

##### SIDEBAR SELECTED ENTRY/ITEM (default: desaturated)
#
```json
"theme_gotham_sidebar_selected_entry_white": true,
"theme_gotham_sidebar_selected_entry_gray": true,
"theme_gotham_sidebar_selected_entry_cyan": true,
"theme_gotham_sidebar_selected_entry_yellow": true,
"theme_gotham_sidebar_selected_entry_desaturated": true,
```

##### SIDEBAR LIGHT ICONS (default: dark)
#
```json
"theme_gotham_sidebar_light_icons": true,
```

##### COMPACT TAB - REDUCED TAB HEIGHT
#
```json
"theme_gotham_compact_tab": true,
```

##### ACTIVE TAB - TEXT COLOR (default: desaturated)
#
```json
"theme_gotham_active_tab_entry_white": true,
"theme_gotham_active_tab_entry_gray": true,
"theme_gotham_active_tab_entry_cyan": true,
"theme_gotham_active_tab_entry_yellow": true,
"theme_gotham_active_tab_entry_desaturated": true,
```

##### MODIFIED TAB - ICON MARKER COLOR (default: cyan)
#
```json
"theme_gotham_modified_tab_marker_white": true,
"theme_gotham_modified_tab_marker_gray": true,
"theme_gotham_modified_tab_marker_cyan": true,
"theme_gotham_modified_tab_marker_yellow": true,
"theme_gotham_modified_tab_marker_desaturated": true,
```

##### AUTOCOMPLETE - KEYWORD COLOR (default: desaturated)
#
```json
"theme_gotham_auto_complete_white": true,
"theme_gotham_auto_complete_gray": true,
"theme_gotham_auto_complete_cyan": true,
"theme_gotham_auto_complete_yellow": true,
"theme_gotham_auto_complete_desaturated": true,
```

##### SCROLLBAR COLORS (default: theme based color)
#
```json
"theme_gotham_vertical_scrollbar_white": true,
"theme_gotham_horizontal_scrollbar_white": true,

"theme_gotham_vertical_scrollbar_gray": true,
"theme_gotham_horizontal_scrollbar_gray": true,

"theme_gotham_vertical_scrollbar_cyan": true,
"theme_gotham_horizontal_scrollbar_cyan": true,

"theme_gotham_vertical_scrollbar_yellow": true,
"theme_gotham_horizontal_scrollbar_yellow": true,

"theme_gotham_vertical_scrollbar_desaturated": true,
"theme_gotham_horizontal_scrollbar_desaturated": true,
```

##### SCROLLBAR THINNESS (default: 4)
#
```json
"theme_gotham_vertical_scrollbar_thickest": true,   //width: 6
"theme_gotham_horizontal_scrollbar_thickest": true,

"theme_gotham_vertical_scrollbar_thicker": true,   //width: 5
"theme_gotham_horizontal_scrollbar_thicker": true,

"theme_gotham_vertical_scrollbar_thinner": true,    //width: 3
"theme_gotham_horizontal_scrollbar_thinner": true,

"theme_gotham_vertical_scrollbar_thinnest": true,   //width: 2
"theme_gotham_horizontal_scrollbar_thinnest": true,

"theme_gotham_vertical_scrollbar_invisible": true,  //width:  0
"theme_gotham_horizontal_scrollbar_invisible": true,
```
