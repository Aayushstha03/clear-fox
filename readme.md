# Custom Firefox `userChrome.css` and Sideberry CSS

This project customizes the Firefox browser interface using a custom `userChrome.css` file and additional CSS for the [Sideberry](https://github.com/mbnuqw/sidebery) extension. The goal is to provide a **clean, minimal vertical tabs interface** with a **toggleable sidebar** for efficient tab management.

## Features

### `userChrome.css` Customizations:
- **Vertical Tabs**: Sideberry is configured to display tabs vertically, with an uncluttered design.
- **Tab groups**: Support for firefox container and simple tab grouping into spaces(via sideberry).
- **Toggleable Sidebar**: Sidebar auto-hides and can be toggled for quick access to bookmarks, history, or extensions like Sideberry. A custom keyboard shortcut can be assigned from sideberry. 
- **Reduced Clutter**: Toolbar icons and navigation buttons (e.g., back, forward, refresh) are styled to have a minimalist look, removing unnecessary borders and visual noise.
- **Compact Layout**: The gap between the URL bar and the top of the screen is minimized for maximum screen real estate.
- **Windows Control Buttons**: Custom positioning for the minimize, maximize, and close buttons, aligning them with the rest of the toolbar icons.

### Sideberry CSS Customizations:
- **Clean Vertical Tabs**: Sideberry’s tab list is simplified for a clean appearance.
- **Responsive Design**: The sidebar and tab list adjust to various screen sizes, making them functional on both large and small displays.

## Installation

### 1. `userChrome.css`
1. Navigate to your Firefox profile folder:
   - Windows: `C:\Users\<YourUserName>\AppData\Roaming\Mozilla\Firefox\Profiles\<ProfileFolder>`
   - macOS: `~/Library/Application Support/Firefox/Profiles/<ProfileFolder>`
   - Linux: `~/.mozilla/firefox/<ProfileFolder>`

2. Inside the profile folder, create a folder named `chrome` if it doesn't already exist.

3. Place the `userChrome.css` file inside the `chrome` folder.

4. Restart Firefox to apply the changes.

### 2. Sideberry Extension CSS
1. Install the Sideberry extension from the [Firefox Add-ons](https://addons.mozilla.org/en-US/firefox/addon/sidebery/).
2. In Sideberry settings, navigate to the "Style" tab.
3. Paste the custom Sideberry CSS provided in the settings field.
4. Save the settings and restart Firefox.

## Customization

If you wish to tweak the customizations further, both the `userChrome.css` and Sideberry CSS files can be easily modified. Some elements you might want to adjust:
- **Tab Width**: Change the width of vertical tabs in the Sideberry CSS.
- **Sidebar Auto-Hide Delay**: Modify the hover delay for the sidebar to expand more quickly or slowly.
- **Toolbar Icon Sizes**: Adjust icon sizes and spacing for a more compact or spaced-out layout.

## Screenshots
![custom theme](<screenshots/Screenshot 2024-10-12 .png>)
- custom theme with firefox color is included in the repo as well.
 
![catppuccin theme](<screenshots/Screenshot 2024-10-13 .png>)
- works great with catppuccin themes as well.
---