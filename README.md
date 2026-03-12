# Monospace Theme

> A cool, focused color system for code editors and terminals — characterized by a blue-gray base and a consistent purple accent.

Monospace is extracted and formalized from Google's IDX Monospace theme. It is characterized by a **cool blue-gray base** that recedes into the background and a **consistent purple accent** that carries every interactive element — buttons, cursors, focus rings, active tab borders, and links — across both flavors. The syntax palette uses muted greens for strings, soft blues for constants and functions, warm yellows for variables, and dusty pinks for keywords. Switching between dark and light feels like changing the lighting in a room, not changing themes.

## Color Palette

### Dark

| Palette          | Hex       | RGB             | HSL               |                                               |
| ---------------- | --------- | --------------- | ----------------- | --------------------------------------------- |
| Background       | `#10151d` | `16, 21, 29`    | `217°, 29%, 9%`   | ![](assets/palette/dark_background.png)       |
| Surface          | `#1f2939` | `31, 41, 57`    | `217°, 30%, 17%`  | ![](assets/palette/dark_surface.png)          |
| Overlay          | `#293444` | `41, 52, 68`    | `216°, 25%, 21%`  | ![](assets/palette/dark_overlay.png)          |
| Muted            | `#333e4f` | `51, 62, 79`    | `216°, 22%, 25%`  | ![](assets/palette/dark_muted.png)            |
| Subtle           | `#3d495a` | `61, 73, 90`    | `215°, 19%, 30%`  | ![](assets/palette/dark_subtle.png)           |
| Foreground       | `#d9dfe7` | `217, 223, 231` | `214°, 23%, 88%`  | ![](assets/palette/dark_foreground.png)       |
| Muted Foreground | `#8b98a9` | `139, 152, 169` | `214°, 15%, 60%`  | ![](assets/palette/dark_muted_foreground.png) |
| Purple           | `#a87ffb` | `168, 127, 251` | `260°, 94%, 74%`  | ![](assets/palette/dark_purple.png)           |
| Blue             | `#92a9ff` | `146, 169, 255` | `227°, 100%, 79%` | ![](assets/palette/dark_blue.png)             |
| Cyan             | `#85cdf1` | `133, 205, 241` | `200°, 79%, 73%`  | ![](assets/palette/dark_cyan.png)             |
| Green            | `#77d5a3` | `119, 213, 163` | `148°, 53%, 65%`  | ![](assets/palette/dark_green.png)            |
| Yellow           | `#ffd395` | `255, 211, 149` | `35°, 100%, 79%`  | ![](assets/palette/dark_yellow.png)           |
| Pink             | `#fd8da3` | `253, 141, 163` | `348°, 97%, 77%`  | ![](assets/palette/dark_pink.png)             |
| Red              | `#f76769` | `247, 103, 105` | `359°, 90%, 69%`  | ![](assets/palette/dark_red.png)              |
| Mauve            | `#bd9cfe` | `189, 156, 254` | `260°, 98%, 80%`  | ![](assets/palette/dark_mauve.png)            |

### Light

| Palette          | Hex       | RGB             | HSL               |                                                |
| ---------------- | --------- | --------------- | ----------------- | ---------------------------------------------- |
| Background       | `#f4f7fd` | `244, 247, 253` | `220°, 69%, 97%`  | ![](assets/palette/light_background.png)       |
| Surface          | `#ffffff` | `255, 255, 255` | `0°, 0%, 100%`    | ![](assets/palette/light_surface.png)          |
| Overlay          | `#e7ebf2` | `231, 235, 242` | `218°, 30%, 93%`  | ![](assets/palette/light_overlay.png)          |
| Muted            | `#d9dfe7` | `217, 223, 231` | `214°, 23%, 88%`  | ![](assets/palette/light_muted.png)            |
| Subtle           | `#bfc7d2` | `191, 199, 210` | `215°, 17%, 79%`  | ![](assets/palette/light_subtle.png)           |
| Foreground       | `#1f2939` | `31, 41, 57`    | `217°, 30%, 17%`  | ![](assets/palette/light_foreground.png)       |
| Muted Foreground | `#738295` | `115, 130, 149` | `214°, 14%, 52%`  | ![](assets/palette/light_muted_foreground.png) |
| Purple           | `#6f4cde` | `111, 76, 222`  | `254°, 69%, 58%`  | ![](assets/palette/light_purple.png)           |
| Blue             | `#264dcb` | `38, 77, 203`   | `226°, 68%, 47%`  | ![](assets/palette/light_blue.png)             |
| Cyan             | `#0075a2` | `0, 117, 162`   | `197°, 100%, 32%` | ![](assets/palette/light_cyan.png)             |
| Green            | `#007b49` | `0, 123, 73`    | `156°, 100%, 24%` | ![](assets/palette/light_green.png)            |
| Yellow           | `#d07826` | `208, 120, 38`  | `29°, 69%, 48%`   | ![](assets/palette/light_yellow.png)           |
| Pink             | `#c43058` | `196, 48, 88`   | `344°, 61%, 48%`  | ![](assets/palette/light_pink.png)             |
| Red              | `#df4047` | `223, 64, 71`   | `357°, 71%, 56%`  | ![](assets/palette/light_red.png)              |
| Mauve            | `#6f4cde` | `111, 76, 222`  | `254°, 69%, 58%`  | ![](assets/palette/light_mauve.png)            |

For details on how these colors map to syntax tokens, see the [Syntax Roles](#syntax-roles) section below.

---

## Base16 Terminal Colors

### Dark

| Token          | Hex       | RGB             |                                               |
| -------------- | --------- | --------------- | --------------------------------------------- |
| Black          | `#738295` | `115, 130, 149` | ![](assets/ansi/dark_ansi_black.png)          |
| Red            | `#f76769` | `247, 103, 105` | ![](assets/ansi/dark_ansi_red.png)            |
| Green          | `#17b877` | `23, 184, 119`  | ![](assets/ansi/dark_ansi_green.png)          |
| Yellow         | `#ffa23e` | `255, 162, 62`  | ![](assets/ansi/dark_ansi_yellow.png)         |
| Blue           | `#708fff` | `112, 143, 255` | ![](assets/ansi/dark_ansi_blue.png)           |
| Magenta        | `#a87ffb` | `168, 127, 251` | ![](assets/ansi/dark_ansi_magenta.png)        |
| Cyan           | `#25a6e9` | `37, 166, 233`  | ![](assets/ansi/dark_ansi_cyan.png)           |
| White          | `#a4afbd` | `164, 175, 189` | ![](assets/ansi/dark_ansi_white.png)          |
| Bright Black   | `#8b98a9` | `139, 152, 169` | ![](assets/ansi/dark_ansi_bright_black.png)   |
| Bright Red     | `#fc8f8e` | `252, 143, 142` | ![](assets/ansi/dark_ansi_bright_red.png)     |
| Bright Green   | `#66ce98` | `102, 206, 152` | ![](assets/ansi/dark_ansi_bright_green.png)   |
| Bright Yellow  | `#ffc26e` | `255, 194, 110` | ![](assets/ansi/dark_ansi_bright_yellow.png)  |
| Bright Blue    | `#a2b6ff` | `162, 182, 255` | ![](assets/ansi/dark_ansi_bright_blue.png)    |
| Bright Magenta | `#c8aaff` | `200, 170, 255` | ![](assets/ansi/dark_ansi_bright_magenta.png) |
| Bright Cyan    | `#71c2ee` | `113, 194, 238` | ![](assets/ansi/dark_ansi_bright_cyan.png)    |
| Bright White   | `#fafbfe` | `250, 251, 254` | ![](assets/ansi/dark_ansi_bright_white.png)   |

### Light

| Token          | Hex       | RGB            |                                                |
| -------------- | --------- | -------------- | ---------------------------------------------- |
| Black          | `#333e4f` | `51, 62, 79`   | ![](assets/ansi/light_ansi_black.png)          |
| Red            | `#d03941` | `208, 57, 65`  | ![](assets/ansi/light_ansi_red.png)            |
| Green          | `#007b49` | `0, 123, 73`   | ![](assets/ansi/light_ansi_green.png)          |
| Yellow         | `#a65921` | `166, 89, 33`  | ![](assets/ansi/light_ansi_yellow.png)         |
| Blue           | `#3c60dd` | `60, 96, 221`  | ![](assets/ansi/light_ansi_blue.png)           |
| Magenta        | `#6f4cde` | `111, 76, 222` | ![](assets/ansi/light_ansi_magenta.png)        |
| Cyan           | `#0075a2` | `0, 117, 162`  | ![](assets/ansi/light_ansi_cyan.png)           |
| White          | `#5d6a7d` | `93, 106, 125` | ![](assets/ansi/light_ansi_white.png)          |
| Bright Black   | `#000000` | `0, 0, 0`      | ![](assets/ansi/light_ansi_bright_black.png)   |
| Bright Red     | `#a52430` | `165, 36, 48`  | ![](assets/ansi/light_ansi_bright_red.png)     |
| Bright Green   | `#00522f` | `0, 82, 47`    | ![](assets/ansi/light_ansi_bright_green.png)   |
| Bright Yellow  | `#904b1a` | `144, 75, 26`  | ![](assets/ansi/light_ansi_bright_yellow.png)  |
| Bright Blue    | `#002487` | `0, 36, 135`   | ![](assets/ansi/light_ansi_bright_blue.png)    |
| Bright Magenta | `#4d21bb` | `77, 33, 187`  | ![](assets/ansi/light_ansi_bright_magenta.png) |
| Bright Cyan    | `#00607e` | `0, 96, 126`   | ![](assets/ansi/light_ansi_bright_cyan.png)    |
| Bright White   | `#475365` | `71, 83, 101`  | ![](assets/ansi/light_ansi_bright_white.png)   |

---

## iTerm2 UI Colors

| Token                       | Dark        | Light     |
| --------------------------- | ----------- | --------- |
| `{{ Background_Color }}`    | `#10151d`   | `#f4f7fd` |
| `{{ Foreground_Color }}`    | `#a4afbd`   | `#475365` |
| `{{ Bold_Color }}`          | `#d9dfe7`   | `#1f2939` |
| `{{ Cursor_Color }}`        | `#c8aaff`   | `#6f4cde` |
| `{{ Cursor_Text_Color }}`   | `#10151d`   | `#f4f7fd` |
| `{{ Selection_Color }}`     | `#264dcb80` | `#c7d3ff` |
| `{{ Selected_Text_Color }}` | `#d9dfe7`   | `#1f2939` |

---

## Syntax Roles

How the palette colors map to code tokens across both flavors.

| Role                    | Dark                 | Light            | Used for                                  |
| ----------------------- | -------------------- | ---------------- | ----------------------------------------- |
| Keywords / Storage      | Pink `#fd8da3`       | Pink `#c43058`   | `if`, `const`, `function`, `class`        |
| Strings                 | Green `#77d5a3`      | Green `#007b49`  | String literals, template literals, regex |
| Constants / Support     | Blue `#92a9ff`       | Blue `#264dcb`   | Numeric constants, built-in support       |
| Variables               | Yellow `#ffd395`     | Yellow `#d07826` | Variable names, parameters                |
| Functions / Classes     | Blue `#92a9ff`       | Blue `#264dcb`   | Function names, class names               |
| Properties / HTML attrs | Cyan `#85cdf1`       | Cyan `#0075a2`   | Object keys, HTML/XML attributes          |
| Tags                    | Green `#77d5a3`      | Green `#007b49`  | HTML/JSX tags                             |
| Types / Entities        | Mauve `#bd9cfe`      | Mauve `#6f4cde`  | Type names, entity names                  |
| Comments                | `#7f8d9f`            | `#637083`        | Inline and block comments                 |
| Errors / Invalid        | Pink Light `#ffc6d0` | Red `#ad1c48`    | Invalid tokens, errors                    |

---

## Ports

### Dark

| Application      | File                                                                                                   |
| ---------------- | ------------------------------------------------------------------------------------------------------ |
| Alacritty        | [`monospace-dark.alacritty.toml`](themes/alacritty/monospace_dark.alacritty.toml)                      |
| Windows Terminal | [`monospace-dark.windows-terminal.json`](themes/windows-terminal/monospace_dark.windows-terminal.json) |
| Warp             | [`monospace_dark.warp.yaml`](themes/warp/monospace_dark.warp.yaml)                                     |

### Light

| Application      | File                                                                                                     |
| ---------------- | -------------------------------------------------------------------------------------------------------- |
| Alacritty        | [`monospace-light.alacritty.toml`](themes/alacritty/monospace_light.alacritty.toml)                      |
| Windows Terminal | [`monospace-light.windows-terminal.json`](themes/windows-terminal/monospace_light.windows-terminal.json) |
| Warp             | [`monospace_light.warp.yaml`](themes/warp/monospace_light.warp.yaml)                                     |

---
