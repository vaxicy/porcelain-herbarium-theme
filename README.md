<p align="center">
  <img src="https://raw.githubusercontent.com/vaxicy/porcelain-herbarium-theme/main/assets/icon.png" alt="Porcelain Botany Theme logo" width="128">
</p>

<h1 align="center">Porcelain Botany Theme</h1>

<p align="center">
  <a href="https://marketplace.visualstudio.com/items?itemName=lilinhuang.porcelain-herbarium-theme"><img src="https://img.shields.io/badge/VS%20Code-Theme-71869B?logo=visual-studio-code" alt="VS Code Theme"></a>
  <img src="https://img.shields.io/badge/version-1.0.0-48515A?logo=visual-studio-code" alt="version 1.0.0">
  <img src="https://img.shields.io/badge/Variants-Light%20%26%20Dark-C4A7B7?logo=visual-studio-code" alt="Light and Dark variants">
  <a href="https://github.com/vaxicy/porcelain-herbarium-theme/blob/main/LICENSE"><img src="https://img.shields.io/badge/license-Non--Commercial-lightgrey" alt="License: Non-Commercial"></a>
</p>

A botanical study pressed onto porcelain: **cream-white paper**, **dusty mauve petals**, **sage leaves** and **blue-gray slate ink**. The light variant reads like a flower album on a sunlit desk; the dark variant is the same album after dusk, paper turned deep slate and ink swapped for pale sage. Both variants are cut from one palette, so switching changes the light level rather than the character of the workspace.

一层瓷白纸上的植物标本：**奶白的纸面**、**干花藕紫**、**鼠尾草绿**与**灰蓝的墨迹**。浅色版像日光下的干花册，深色版是入夜后的同一本册子——纸面沉为深石板，墨色换成浅鼠尾草。两套变体同出一套色板，切换时改变的是明暗而非气质。

## Preview / 预览

| Light 浅色 | Dark 深色 |
| --- | --- |
| ![Porcelain Botany Theme Light](https://raw.githubusercontent.com/vaxicy/porcelain-herbarium-theme/main/store-assets/screenshots/en/screenshot-light.png) | ![Porcelain Botany Theme Dark](https://raw.githubusercontent.com/vaxicy/porcelain-herbarium-theme/main/store-assets/screenshots/en/screenshot-dark.png) |

> Both previews are captured from a real VS Code window running the theme — no mockups.
>
> 上方预览图取自真实运行该主题的 VS Code 窗口截图，非模拟图。

## Palette / 色板

| Role | Light | Dark |
| --- | --- | --- |
| Editor background | `#FFFBF4` porcelain cream | `#2B3032` deep slate |
| Ink (foreground) | `#4A5052` warm slate | `#E2E5DE` pale sage |
| Muted text / placeholders | `#7E8872` | `#8F9B7F` |
| Side bar | `#F5F1EA` with `#54604E` text | `#2C3431` with `#C3CEBD` text |
| Panel / terminal | `#FDF5E4` | `#292E2E` |
| Title bar | `#F0E7EA` with `#4D5968` text | `#25282A` with `#CAD2DA` text |
| Tab bar / inactive tab | `#ECEFE8` | `#222A2C` |
| Active tab indicator | `#B38D9F` mauve | `#E0C2D7` pale mauve |
| Activity bar | `#E7DDE0` with `#5D7288` icons | `#202426` with `#A3C2BD` icons |
| Status bar | `#E5D6DC` with `#536348` text | `#405450` with `#DCE7CF` text |
| Selection | `#DCE5D0` sage wash | `#4D6047` deep sage |
| Current line | `#FBF2DF` | `#343D3F` |
| Borders / indent guides | `#D8DFD4` / `#E5E7DD` | `#414D43` / `#404B42` |
| Buttons | `#C9D8BB` with `#46553E` text (hover `#BFCEAD`) | `#C9D8BB` with `#2D3C27` text (hover `#DFE8D2`) |
| Badge | `#71869B` with `#FFFFFF` text | `#A3C2BD` with `#2B3032` text |
| Cursor | `#71869B` | `#FDF5E4` |
| Links | `#758C58` | `#CED8C2` |
| Errors / warnings | `#B05E65` / `#9C7B42` | `#E3A4AA` / `#E6CCA0` |
| Git added / modified / deleted | `#789C95` / `#A48657` / `#B3797E` | `#BCD2A8` / `#E0C59D` / `#DDA6AE` |

Brand palette: porcelain cream `#FBF2DF`, sage `#BCD2A8`, dusty mauve `#C4A7B7`, slate blue `#71869B`, deep slate `#2B3032`.

品牌色板：瓷白 `#FBF2DF`、鼠尾草绿 `#BCD2A8`、干花藕紫 `#C4A7B7`、灰蓝 `#71869B`、深石板 `#2B3032`。

## Syntax mapping / 语法映射

| Syntax | Light | Dark |
| --- | --- | --- |
| Comments | `#929B87` italic | `#91A087` italic |
| Keywords, storage, tags | `#92718E` dusty mauve | `#E0C2D7` (tags `#F6DBD8`) |
| Strings | `#6F8E75` sage | `#C9D8BB` |
| Regexp | `#89A26A` | `#D1DBC5` |
| Escapes | `#9B7954` | `#E8C79B` |
| Numbers / constants | `#A07845` amber ink | `#FDF5E4` |
| Types / classes / interfaces | `#847296` mauve | `#D4C3DF` |
| Functions / methods | `#5C8290` slate blue | `#A3C2BD` |
| Properties | `#54817B` | `#B6D2C7` |
| Variables | `#4A5052` | `#E2E5DE` |
| Parameters | `#81785D` | `#D4CDB5` |
| Operators | `#78816F` | `#BBC6B2` |
| Punctuation | `#91998A` | `#9FAE9B` |
| Attributes | `#A07845` | `#FDF5E4` |
| Headings / bold / italic | `#4D5C3A` | `#ECF0E6` |
| Invalid | `#B65353` | `#E99B91` |

Dusty mauve carries keywords, storage and tags, so markup and control flow read as one family; sage green carries strings, and slate blue carries functions. Types reuse the mauve to tie declarations together, while amber numbers, constants and attributes stay warm to keep your eye anchored while scanning.

干花藕紫承担关键字、storage 与标签，让标记语言与控制流读起来是一族；鼠尾草绿给字符串，灰蓝给函数。类型沿用藕紫，把各类声明串成一脉；琥珀色的数字、常量与属性保持暖调，扫读时才有落点。

## Coverage / 覆盖范围

Every surface below is themed in both variants (144 UI colors each):

- **Editor** — background, foreground, selection and inactive selection, current-line highlight, word and selection highlights, find match and find highlight, bracket-match background and border, cursor, line numbers (plus the active line number), indent guides, whitespace, ruler, errors, warnings and info.
- **Workbench chrome** — activity bar, badge and active border, title bar (active and inactive), side bar with section headers and border, status bar (normal, no-folder and debugging states), editor group header and tabs (active, inactive, hover, modified border and active top border).
- **Panels and overlays** — panel, editor widgets, hover widget, suggest widget, dropdowns, inputs and placeholder text, notifications, quick input, and the focus border.
- **Lists** — active, inactive and hover selection backgrounds, plus the highlight and focus-highlight colors, and tree indent guides.
- **Terminal** — background, foreground and the full 16-color ANSI palette, matched to the theme.
- **Details** — workbench borders, scrollbar sliders, git decoration colors (added / modified / deleted) with their gutter markers, buttons, badges, diff editor backgrounds, and semantic token colors for variable, parameter, property, function, method, type, class and interface.

以下区域在两套变体中均已配色（每套 144 个 UI 颜色）：编辑器本体（选区与失焦选区、当前行、词/选区高亮、查找匹配与高亮、括号匹配、光标、行号、标尺、缩进线、空白符、错误/警告/提示）；活动栏与角标、标题栏、侧边栏（含分节标题）、状态栏（含无文件夹与调试态）、标签栏；面板与各类浮窗（悬停、建议、通知、快速输入）、下拉与输入框、列表选中/悬停/高亮、树缩进线；终端 ANSI 全色；全部边框与滚动条、Git 装饰色与 gutter 标记、按钮与角标、差异编辑器底色，以及变量/参数/属性/函数/方法/类型/类/接口的语义高亮。完整的颜色清单见 `COLOR-SPEC.md`。

## Features / 功能

- **Two coordinated variants** — `Porcelain Botany Theme Light` and `Porcelain Botany Theme Dark` ship in one extension.
- **One porcelain palette** — cream and warm-sand surfaces in light, deep slate in dark, with sage, mauve and slate-blue accents.
- **Readable syntax colors** — dusty-mauve keywords, sage strings, slate-blue functions and amber numbers, tuned for contrast on both backgrounds.
- **Semantic highlighting** enabled, so language-aware tokens are colored beyond the classic TextMate scopes.
- **Terminal ANSI colors** taken from the same palette, so the integrated terminal sits inside the theme.

- **明暗两套协调变体**——同一扩展内含 `Porcelain Botany Theme Light` 与 `Porcelain Botany Theme Dark`。
- **一套瓷白植物色板**——浅色为瓷白与暖砂的底色，深色为深石板，配鼠尾草绿、藕紫与灰蓝点缀。
- **可读的语法配色**——藕紫的关键字、鼠尾草绿的字符串、灰蓝的函数与琥珀色数字，在明暗底色上都保持对比。
- **启用语义高亮**，在传统 TextMate scope 之外为语言感知的 token 着色。
- **终端 ANSI 配色**取自同一色板，集成终端与主题融为一体。

## Installation / 安装

Requires VS Code 1.80 or newer.

1. Search for **Porcelain Botany Theme** in the Extensions view (`Ctrl+Shift+X` / `Cmd+Shift+X`), or open the [Marketplace page](https://marketplace.visualstudio.com/items?itemName=lilinhuang.porcelain-herbarium-theme).
2. Or install from a VSIX: download `porcelain-herbarium-theme-1.0.0.vsix`, open the Command Palette (`Ctrl+Shift+P` / `Cmd+Shift+P`) and run **Extensions: Install from VSIX...**.

需要 VS Code 1.80 或更高版本。

1. 在扩展面板（`Ctrl+Shift+X` / `Cmd+Shift+X`）搜索 **Porcelain Botany Theme**，或打开 [Marketplace 页面](https://marketplace.visualstudio.com/items?itemName=lilinhuang.porcelain-herbarium-theme)。
2. 也可以从 VSIX 安装：下载 `porcelain-herbarium-theme-1.0.0.vsix`，打开命令面板（`Ctrl+Shift+P` / `Cmd+Shift+P`），运行 **Extensions: Install from VSIX...** 并选择该文件。

Or from the command line:

或使用命令行：

```
ext install lilinhuang.porcelain-herbarium-theme
```

## Activation / 启用

Open the Command Palette (`Ctrl+Shift+P` / `Cmd+Shift+P`), run **Preferences: Color Theme**, and choose **Porcelain Botany Theme Light** or **Porcelain Botany Theme Dark**.

To switch between the two variants quickly, use the keyboard shortcut `Ctrl+K Ctrl+T` at any time.

打开命令面板（`Ctrl+Shift+P` / `Cmd+Shift+P`），运行 **Preferences: Color Theme**，选择 **Porcelain Botany Theme Light** 或 **Porcelain Botany Theme Dark**。

随时可用快捷键 `Ctrl+K Ctrl+T` 在两套变体之间快速切换。

## Development / 开发

Open this folder in VS Code and press `F5` to launch an Extension Development Host with the theme loaded.

在 VS Code 中打开本文件夹并按 `F5`，在扩展开发宿主中预览主题。

Regenerate the real-window preview screenshots with:

重新生成真实窗口预览图：

```bash
python scripts/capture-real-screenshots.py            # both variants
python scripts/capture-real-screenshots.py light      # one variant
```

The script builds a throwaway VS Code profile in a temp directory, installs this theme into it, opens the sample project under `scripts/demo-project`, captures the window (cropping the OS window frame), and writes the result to `store-assets/screenshots/en/`.

脚本会在临时目录里创建一个独立的 VS Code 配置，把本主题装进去，打开 `scripts/demo-project` 示例工程，截取窗口（并裁掉系统窗口边框），输出到 `store-assets/screenshots/en/`。

Check a build before publishing:

发布前自查：

```bash
python scripts/validate.py
```

It refreshes `COLOR-SPEC.md` from the theme JSON files, verifies that every color value is a valid hex code, checks that the screenshot edges match `titleBar.activeBackground`, and — when a `.vsix` is present — verifies the manifest publisher, version and theme entries.

脚本会依据主题 JSON 重新生成 `COLOR-SPEC.md`，校验所有颜色值均为合法十六进制，检查截图首行/首列与 `titleBar.activeBackground` 一致，并在存在 `.vsix` 时校验清单里的发布者、版本与主题条目。

Package the extension with:

打包扩展：

```bash
vsce package
```

## License / 许可

Released under the **Non-Commercial License** — licensed for personal, educational and non-commercial use. See [LICENSE](LICENSE) for details.

基于 **Non-Commercial License（非商业使用许可）** 发布，可用于个人、教育及非商业用途，详见 [LICENSE](LICENSE)。

## Feedback / 反馈

Found an unthemed area or want a tweak? Open an issue at [github.com/vaxicy/porcelain-herbarium-theme/issues](https://github.com/vaxicy/porcelain-herbarium-theme/issues).

发现没有配色的区域或想调整某处颜色，欢迎在 [GitHub Issues](https://github.com/vaxicy/porcelain-herbarium-theme/issues) 反馈。

## Publisher / 发布者

Published by **lilinhuang** on the Visual Studio Code Marketplace.

由 **lilinhuang** 发布于 Visual Studio Code Marketplace。
