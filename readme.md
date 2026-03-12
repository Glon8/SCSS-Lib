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

- **name** – The font name used to reference it in the library.
- **color** – Color you choosed.

> **Note:** Suggested to pick up colors on sites for color pallets.

### Example: 

**Site** 

```scss
https://colorpalettes.net/
```

**Format**

```scss
name: color,
```

---

## Fonts Guide

> **Note:** This section is intended for adding **local fonts**.

Each font entry requires the following fields:

- **name** – The font name used to reference it in the library
- **dest** – Path to the font file (including the file extension)
- **format** – Font format (`truetype`, `opentype`, etc.)

### Example

```scss
(name: 'name', dest: 'path/to/font-file', format: 'file-format'),
```

---

## Images Guide

> **Note:** This section is intended for adding **local images**.

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