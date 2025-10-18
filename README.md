# ZettlrCustomCSS-Simple
Customizing Zettlr interface to make it simple and pure. Light theme only, for now.

## 🖼️ Screenshot
![Screenshot](assets/2025-10-18_screenshot_zettlr.png)

## 🎨What I changed
Generally, I wanted to have a simple, clean interface. Please note that these are my very personal tastes, feel free to change the CSS to your tastes 😊
Here is a non-exhaustive of the things that are overriden with this custom CSS theme.
- **General**: Unified the background colors to be all white, removed some border, only kept a rounder border around the editing area
- **Main text**: Changed font and tweaked color and size a bit
- **Horizontal lines** `---`: Full-width, thicker and grey, still show the dashes for easier edition
- **Quotes**: Gray background, change font color when selected (otherwise the selection is not visible)
- **Headings**: Changing the color of the `#` symbols of heading (which I like to keep visible for easier editing)
- **Tabs**: Made them rounder, grey and darker when selected
- **Right panel**: Similar: grey rounded button, removed numeric part of the TOC (very personal choice for simplicity)
- **Buttons**:  Again: grey rounded buttons for general buttons (eg "Export")
- **Left panel**: Hiding the directory / workspace as I don't use it personally, made the "Filter" field also white background
- **Scrollbar**: Also simplified, rounded and removed borders

## 💾 How to install?
1. In Zettlr, open the "Assets Manager" (Can be found in "File" → "Preference" or sometimes with shortcut `CTRL + ALT + ,`)
2. Go to "Custom CSS" tab
3. Paste there the content of the file [custom_theme.css](custom_theme.css)
4. Customize it according to your taste
4. Save
They changes should immediately be applied.

## ⚠️ Disclaimer
I am using Linux Fedora 42 KDE, Zettlr version 3.6.0 installed from Flatpak. I am using in light theme. Any deviation from this might not render the theme correctly.

To adapt the theme to your case and taste, I strongly recommend to use the inspector, as documented in Zettlr [docs](https://docs.zettlr.com/en/advanced/custom-css/#tips-for-finding-selectors).
The idea is simply to identify the correct and complete handles for the elements to change and their variables like `color`, `background`, `border`... LLM can also also help but I found it quite dumb for CSS editing and I would say that it is worth knowing tweaking the theme yourself,