# Dwoply syntax theme for Godot 4.x

A vibrant syntax theme inspired by Monokai.

**TODO:** `bookmark_color`, `breakpoint_color` and `executing_line_color` haven't been setup yet.

## Installation

Place the `.tet` file in your Godot text editor theme directory:

- On Linux: `~/.config/godot/text_editor_themes/`
- On macOS: `~/Library/Application Support/Godot/text_editor_themes/`
- On Windows: `%APPDATA%\Godot\text_editor_themes\`
- On Android: check below.

**Note:** If you installed Godot using Steam, your Godot text editor theme folder should be placed in `steamapps/common/Godot Engine/editor_data/text_editor_themes/` in your Steam installation folder.

To change the theme, open a project in the editor, click on **Editor** in the top menu, then go to the **Editor Settings** then **Text Editor**. You should now be able to choose the desired theme.

**Tip:** You can clone this Git repository directly into the text editor themes path (if the destination folder does not exist) using the following command:

```bash
# On Linux:
git clone https://github.com/godotengine/dwoply-syntax-theme.git ~/.config/godot/text_editor_themes

# On macOS:
git clone https://github.com/godotengine/dwoply-syntax-theme.git "~/Library/Application Support/Godot/text_editor_themes"

# On Windows:
git clone https://github.com/godotengine/dwoply-syntax-theme.git "%APPDATA%\Godot\text_editor_themes"
```

### Android

1. Download the desired editor theme file (in `.tet` format).
2. In the editor's Script tab, go to **File > Theme > Import Theme...**.
3. Select the `.tet` file in the dialog.
