# SCSS-lib

**SCSS-lib** is my custom **SASS library**, originally created for personal use but freely available for anyone to use.  
It was rebuilt and organized from my previous code to be **modular, flexible, and easy to modify**.

In the future, I plan to build my own UI components based on this library.

## Customization

To modify values such as measurements, colors, fonts, breakpoints etc:

1. Open:  
   `scss-lib/core/_variables.scss`
2. Edit the lists according to your needs.

> **Note:** Changing values in these lists will affect the entire library.

---

## Colors Guide

1. Find css color.
2. Open `scss-lib/core/_variables.scss`.
3. Add color as described below to `colors` list.

Each font entry requires the following fields:

- **name** – The font name used to reference it in the library.
- **color** – Color you choosed (hex, rgb, etc).

> **Note:** Good site for colors `https://colorpalettes.net`.

### Example:

```scss
name: color,
```

---

## Fonts Guide

### Custom Font

> **Note:** This section is intended for adding **local fonts / custom fonts**.

1. Download custom font.
2. Add font files to your project.
3. Open `scss-lib/core/_variables.scss`.
4. Add custom font as described below to `fonts-custom` list.

Each font entry requires the following fields:

- **name** – The font name used to reference it in the library.
- **dest** – Path to the font file (including the file extension)
- **format** – Font format (`truetype`, `opentype`, etc.)

> **Note:** Good site for fonts `https://www.1001fonts.com`.

### Example

```scss
(name: 'name', dest: 'path/to/font-file', format: 'file-format'),
```

### Built-in Font

> **Note:** This section is intended for adding **built-in font**.

1. Find css font.
2. Open `scss-lib/core/_variables.scss`.
3. Add font as described below to `fonts` list.

Each font entry requires the following fields:

- **name** – The font name used to reference it in the library.
- **font** - Existing font in css.

### Example

```scss
(name: font),
```

---

## Images Guide

> **Note:** This section is intended for adding **local images**.

1. Download custom image.
2. Add image file to your project.
3. Open `scss-lib/core/_variables.scss`.
4. Add image as described below to `images` list.

Each image entry requires the following fields:

- **name** – The font name used to reference it in the library.
- **path** – Path to the font file (including the file extension)

### Example

```scss
name: url('path/to/image'),
```

## Installation:

1. Install **SASS** in to your project.
2. Download folder `scss-lib`.
3. Link `scss-lib.scss` file in your project.

**DONE!**