# GitHub Themes for IntelliJ

[![Version](https://img.shields.io/jetbrains/plugin/v/20810-github-themes.svg)](https://plugins.jetbrains.com/plugin/20810-github-themes)
[![Downloads](https://img.shields.io/jetbrains/plugin/d/20810-github-themes.svg)](https://plugins.jetbrains.com/plugin/20810-github-themes)

GitHub's VS Code themes for JetBrains IDEs. Your code looks the same as it does in VS Code, and the rest of the IDE uses GitHub's colors.

Works in IntelliJ IDEA, PhpStorm, WebStorm, PyCharm, GoLand, RubyMine, RustRover, CLion, Rider, DataGrip, Android Studio and other JetBrains IDEs.

---

## What you get

- **11 themes:** 6 dark and 5 light, including colorblind, tritanopia and high contrast versions.
- **Matching editor colors:** each theme comes with its own editor color scheme, applied automatically.
- **Code colored like VS Code:** syntax colors come straight from GitHub's VS Code themes, in every language your IDE supports: PHP, JavaScript, TypeScript, CSS, HTML, Java, Kotlin, Python, Go, Rust, Ruby, C, C++, C#, SQL, Markdown, YAML and many more.
- **GitHub colors everywhere:** popups, tooltips, notifications, the terminal, diffs, Git, the debugger and the Welcome screen.
- **Made for the Islands UI:** the editor and tool windows sit on one surface, and the toolbar, status bar and side stripes on another.
- **Easy to read:** text, links, buttons and selections meet WCAG AA contrast in every theme.

## Which theme should I pick?

| Theme | Best for |
|---|---|
| **Github - Dark Default** | GitHub's current dark theme. A good default. |
| **Github - Dark Dimmed** | A softer, lower-contrast dark theme that is easier on the eyes at night. |
| **Github - Dark** | GitHub's classic dark theme. |
| **Github - Dark Colorblind** | Red–green color blindness. Success is blue and errors are orange. |
| **Github - Dark Tritanopia** | Blue–yellow color blindness. Success is blue and errors stay red. |
| **Github - Dark High Contrast** | Low vision. Stronger text, borders and highlights. |
| **Github - Light Default** | GitHub's current light theme. A good default. |
| **Github - Light** | GitHub's classic light theme. |
| **Github - Light Colorblind** | Red–green color blindness. Success is blue and errors are orange. |
| **Github - Light Tritanopia** | Blue–yellow color blindness. Success is blue and errors stay red. |
| **Github - Light High Contrast** | Low vision. Stronger text, borders and highlights. |

## Requirements

- A JetBrains IDE with the **new UI**. The themes do not appear in the classic UI.
- The themes are designed for JetBrains' **Islands** UI and look best in **2025.3 or later**.
- For the exact IDE versions each plugin version supports, see the [Marketplace page](https://plugins.jetbrains.com/plugin/20810-github-themes/versions).

## Installation

- **From the IDE:**
  <kbd>Settings</kbd> > <kbd>Plugins</kbd> > <kbd>Marketplace</kbd> > search for **"GitHub Themes"** > <kbd>Install</kbd>

- **Manually:**
  Download `github-theme.jar` from [Releases](../../releases) or the [JetBrains Marketplace](https://plugins.jetbrains.com/plugin/20810-github-themes/versions), then use
  <kbd>Settings</kbd> > <kbd>Plugins</kbd> > <kbd>⚙️</kbd> > <kbd>Install plugin from disk...</kbd>

## Switching themes

1. Open <kbd>Settings</kbd> > <kbd>Appearance & Behavior</kbd> > <kbd>Appearance</kbd>.
2. Pick a **Github - …** theme from the **Theme** list.

The matching editor colors switch with it.

To follow your system's light and dark mode, turn on **Sync with OS** next to the Theme list and choose one GitHub theme for light and one for dark.

The themes change colors only. Your editor font and size stay as they are (<kbd>Settings</kbd> > <kbd>Editor</kbd> > <kbd>Font</kbd>).

## Customizing colors

To change a color without losing it when the plugin updates, edit a copy of the color scheme:

1. Open <kbd>Settings</kbd> > <kbd>Editor</kbd> > <kbd>Color Scheme</kbd> and select your **Github - …** scheme.
2. Click <kbd>⚙️</kbd> > <kbd>Duplicate...</kbd> and give the copy a name.
3. Change colors in the copy.

Your copy keeps your changes, but it won't receive color fixes from later plugin updates.

## Updates and uninstalling

- **Updates:** the IDE checks for plugin updates and offers to install them. If you installed from the Marketplace, it always gets the latest version that works with your IDE.
- **Switching back:** pick another theme in <kbd>Settings</kbd> > <kbd>Appearance & Behavior</kbd> > <kbd>Appearance</kbd>.
- **Uninstalling:** <kbd>Settings</kbd> > <kbd>Plugins</kbd> > <kbd>Installed</kbd> > **Github Themes** > <kbd>Uninstall</kbd>. The IDE goes back to its default theme.

## Troubleshooting

- **The editor colors didn't change.** Go to <kbd>Settings</kbd> > <kbd>Editor</kbd> > <kbd>Color Scheme</kbd> and pick the scheme with the same name as your theme, for example *Github - Dark Default*.
- **Some colors still look off after an update.** If you changed the color scheme yourself, the IDE keeps your copy. Select the scheme, then <kbd>⚙️</kbd> > <kbd>Restore Defaults</kbd>.
- **The themes are not in the list.** The themes only appear in the new UI. From 2024.2 the new UI is the default; if you use the *Classic UI* plugin, disable it. In older IDEs, turn it on in <kbd>Settings</kbd> > <kbd>Appearance & Behavior</kbd> > <kbd>New UI</kbd>.

## What's new

See [Releases](../../releases) for the changes in each version.

## Reporting an issue

Found a color that looks wrong, something hard to read, or a compatibility problem?
[Open an issue](../../issues/new/choose) and include:

- the theme name (for example *Github - Dark Default*),
- your IDE and version (<kbd>Help</kbd> > <kbd>About</kbd>),
- the plugin version,
- a screenshot of the problem.

Theme and color requests are welcome too.

## Support the project

If you like the themes, please [rate and review them on the JetBrains Marketplace](https://plugins.jetbrains.com/plugin/20810-github-themes/reviews). It helps other people find them.

## License

Copyright © 2023–2026 Yash Pal. All rights reserved. See [LICENSE](LICENSE).

Free to use in your JetBrains IDEs. Copying, modification or redistribution is not permitted without written permission.

Colors are based on [GitHub Primer](https://github.com/primer/primitives) (MIT License) and [GitHub's VS Code themes](https://github.com/primer/github-vscode-theme) (MIT License). This plugin is not affiliated with or endorsed by GitHub, Inc.
