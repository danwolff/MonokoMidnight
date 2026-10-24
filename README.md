# MonokoMidnight

<table>
  <tr>
    <td align="center"><a href="https://raw.githubusercontent.com/danwolff/MonokoMidnight/main/Screenshots/6.png"><img src="https://raw.githubusercontent.com/danwolff/MonokoMidnight/main/Screenshots/Thumbs/6.png" width="260" alt="MonokoMidnight with Python"></a><br><sub>Python</sub></td>
    <td align="center"><a href="https://raw.githubusercontent.com/danwolff/MonokoMidnight/main/Screenshots/4.png"><img src="https://raw.githubusercontent.com/danwolff/MonokoMidnight/main/Screenshots/Thumbs/4.png" width="260" alt="MonokoMidnight with JavaScript"></a><br><sub>JavaScript</sub></td>
    <td align="center"><a href="https://raw.githubusercontent.com/danwolff/MonokoMidnight/main/Screenshots/1.png"><img src="https://raw.githubusercontent.com/danwolff/MonokoMidnight/main/Screenshots/Thumbs/1.png" width="260" alt="MonokoMidnight with HTML"></a><br><sub>HTML</sub></td>
  </tr>
  <tr>
    <td align="center"><a href="https://raw.githubusercontent.com/danwolff/MonokoMidnight/main/Screenshots/2.png"><img src="https://raw.githubusercontent.com/danwolff/MonokoMidnight/main/Screenshots/Thumbs/2.png" width="260" alt="MonokoMidnight with JSON"></a><br><sub>JSON</sub></td>
    <td align="center"><a href="https://raw.githubusercontent.com/danwolff/MonokoMidnight/main/Screenshots/9.png"><img src="https://raw.githubusercontent.com/danwolff/MonokoMidnight/main/Screenshots/Thumbs/9.png" width="260" alt="MonokoMidnight with CSS"></a><br><sub>CSS</sub></td>
    <td align="center"><a href="https://raw.githubusercontent.com/danwolff/MonokoMidnight/main/Screenshots/5.png"><img src="https://raw.githubusercontent.com/danwolff/MonokoMidnight/main/Screenshots/Thumbs/5.png" width="260" alt="MonokoMidnight with Markdown"></a><br><sub>Markdown</sub></td>
  </tr>
  <tr>
    <td align="center"><a href="https://raw.githubusercontent.com/danwolff/MonokoMidnight/main/Screenshots/7.png"><img src="https://raw.githubusercontent.com/danwolff/MonokoMidnight/main/Screenshots/Thumbs/7.png" width="260" alt="MonokoMidnight with Bash"></a><br><sub>Bash</sub></td>
    <td align="center"><a href="https://raw.githubusercontent.com/danwolff/MonokoMidnight/main/Screenshots/8.png"><img src="https://raw.githubusercontent.com/danwolff/MonokoMidnight/main/Screenshots/Thumbs/8.png" width="260" alt="MonokoMidnight with YAML"></a><br><sub>YAML</sub></td>
    <td align="center"><a href="https://raw.githubusercontent.com/danwolff/MonokoMidnight/main/Screenshots/3.png"><img src="https://raw.githubusercontent.com/danwolff/MonokoMidnight/main/Screenshots/Thumbs/3.png" width="260" alt="MonokoMidnight with Diff"></a><br><sub>Diff</sub></td>
  </tr>
</table>

Sublime Text's built-in **Monokai** color scheme (from `Color Scheme - Default`,
Sublime Text build 4200) with a pure black background (`#000000`) in place of
Monokai's dark olive/brown `hsl(70, 8%, 15%)` (`#272822`).

Only two lines differ from the original:

- `"name"`: `Monokai` → `MonokoMidnight`
- `globals.background`: `var(black3)` → `var(black)` (`hsl(0, 0%, 0%)`)

The other colors are the same as in Monokai: syntax, selection, line highlight, gutter, diff, and so on.

MonokoMidnight is a fork of Sublime Text's built-in Monokai, taken at build 4200.
It doesn't aim to track upstream Monokai, but may pick up upstream changes when
they make sense. The name nods to Monokai, and "Midnight" to the pure black
background.

## Install

### Package Control

1. **Command Palette** → **Package Control: Install Package** → **MonokoMidnight**.
   - Press <kbd>Cmd</kbd>+<kbd>Shift</kbd>+<kbd>P</kbd> on Mac (<kbd>Ctrl</kbd>+<kbd>Shift</kbd>+<kbd>P</kbd>
     on Windows/Linux) to open the Command Palette.
   - Type `insta` and press <kbd>Enter</kbd> on **Package Control: Install Package**.
   - Type `monokomid`, pick **MonokoMidnight** with <kbd>↑</kbd>/<kbd>↓</kbd>, and press <kbd>Enter</kbd> to install it.
2. **Preferences → Select Color Scheme…** → choose **MonokoMidnight**.
   - Open the Command Palette again (<kbd>Cmd</kbd>+<kbd>Shift</kbd>+<kbd>P</kbd> on Mac or
     <kbd>Ctrl</kbd>+<kbd>Shift</kbd>+<kbd>P</kbd> on Windows/Linux), type `color sch`, and press
     <kbd>Enter</kbd> on **UI: Select Color Scheme**.
   - Type `monokomid`. Moving with <kbd>↑</kbd>/<kbd>↓</kbd> previews each scheme live.
     Press <kbd>Enter</kbd> to apply it.

### Manual

1. In Sublime Text: **Preferences → Browse Packages…**
2. Copy `MonokoMidnight.sublime-color-scheme` into the `User` folder.
3. **Preferences → Select Color Scheme…** → choose **MonokoMidnight**.

Or set it in `Preferences.sublime-settings`:

```json
"color_scheme": "MonokoMidnight.sublime-color-scheme"
```

## License

The Chambana License, an MIT-style license. See [LICENSE](LICENSE).

Monokai is by Wimer Hazenberg, and Sublime Text's version of it is by Sublime HQ
Pty Ltd. The license covers only the changes in this package.
