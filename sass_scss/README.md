# Holberton Sass Tasks

This repository contains solutions for 12 main Sass tasks. Each task has its own Sass file, and commands to test the output are provided.

---

## Tasks Overview

### 0. Debug Log
- Print a debug message "Hello world" using Sass debug.
- File: `0-debug_log.scss`
- Test: `sass 0-debug_log.scss`

### 1. Color Variable
- Create a Sass variable for color and assign it to `body` and `p` text.
- File: `1-color_variable.scss`
- Test: `sass 1-color_variable.scss`

### 2. Colors
- Use two Sass variables: one for text color, one for background color.
- Assign text color to `body` and `p`, background color to `body` and `h2`.
- File: `2-color_variables.scss`
- Test: `sass 2-color_variables.scss`

### 3. Nested Tag
- Set `margin` and `padding` of `body` to 0.
- Set `margin` 10px for `p` tags inside `body`.
- Use nested Sass syntax.
- File: `3-nested_tag.scss`

### 4. Nested Class
- Set text color `#3D3D3D` for elements inside `body`.
- Set text color `#FF0000` for `.red` class inside `body`.
- Use nested Sass syntax.
- File: `4-nested_class.scss`

### 5. Nested Child
- Set text color `#3D3D3D` for elements inside `body`.
- Set text color `#FF0000` for `.red` class that is a direct child of `body`.
- Use nested Sass syntax.
- File: `5-nested_child.scss`

### 6. Nested Hover
- Set button text color to `#FF0000`.
- On hover, set button text color to `#00FF00`.
- Use nested Sass syntax.
- File: `6-nested_hover.scss`

### 7. Nested and Nested Again
- Set `font-size: 14px` for `body`.
- Set `font-size: 16px` for `h1` inside `body`.
- Set `font-size: 12px` for `h1.smaller` inside `body`.
- Use nested Sass syntax.
- File: `7-nested_deeper.scss`

### 8. Margin Mixin
- Create a mixin for margin-left and margin-right.
- Apply `10px` margin to `body`, `15px` to `div`.
- File: `8-mixin_margins.scss`

### 9. Extended
- Create `.info` class with `font-size: 12px`.
- `.success` and `.warning` extend `.info`.
- `.success` text color: `#00FF00`.
- `.warning` text color: `#FF0000`.
- File: `9-extend_list.scss`

### 10. Import Colors
- Import colors from `10-colors.scss`.
- Use variables `$red`, `$green`, `$blue` to set text colors for `.red`, `.green`, `.blue`.
- File: `10-import_colors.scss`

### 11. For Each Loop
- Import list of names from `11-photos.scss`.
- Create a class `.photo-<name>` for each name.
- Set background image with `image-url("photos/<name>.jpg")`.
- Use `@use` and `@each`.
- File: `11-loop_photos.scss`

### 12. Loop Headers
- Create `h1` to `h5` tags.
- Set font-size equal to the header number in pixels (`h1` = 1px, `h2` = 2px, etc.).
- Use `@for` loop.
- File: `12-loop_header.scss`

---

## How to Test

Run:

```bash
sass <filename>.scss
