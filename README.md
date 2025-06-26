# Raznor Obsidian theme for Home Assistant
<p align="left">
  <a href="https://github.com/hacs/default" target="_blank"><img src="https://img.shields.io/badge/HACS-Default-21B4F0.svg?style=for-the-badge" alt="HACS Default"></a>
  <a href="https://github.com/Raznor09/raznor-obsidian/releases/latest" target="_blank"><img src="https://img.shields.io/github/v/release/Raznor09/raznor-obsidian?style=for-the-badge" alt="GitHub Release"></a>
  <a href="https://github.com/Raznor09/raznor-obsidian/releases" target="_blank"><img src="https://img.shields.io/github/downloads/Raznor09/raznor-obsidian/total?style=for-the-badge" alt="Total Downloads"></a>
</p>
- A clean, all-black theme with multiple color variants, designed for a minimalist and modern look.
- This single file provides several pre-configured color options, including 🔵Blue, 🟣Purple, 🟢Green, 🔴Red and 🟠Orange.

## Installation

To use this theme, you have two options: manual installation or installation via HACS.

### Manual Installation

1.  **Create a `themes` folder:** In your Home Assistant `config` folder, create a new folder named `themes` if it doesn't already exist.
2.  **Copy the file:** Place the `raznor-obsidian.yaml` file from this repository into that `themes` folder.
3.  **Enable themes in `configuration.yaml`:** Add the following to your `configuration.yaml` file. If you already have a `frontend` section, just add the `themes: !include_dir_merge_named themes` line.

    ```yaml
    frontend:
      themes: !include_dir_merge_named themes
    ```
4.  **Reload & Select:** Restart Home Assistant or reload your themes via Developer Tools > Services (`frontend.reload_themes`).
5.  Then, go to your Profile page and select your preferred color variant from the Theme dropdown. The options are:
    * 🔵 `Raznor Obsidian -` <font color="#53B3FF">Blue</font>
    * 🟣 `Raznor Obsidian -` <font color="#7E1AB2">Purple</font>
    * 🟢 `Raznor Obsidian -` <font color="#1AB21A">Green</font>
    * 🔴 `Raznor Obsidian -` <font color="#FF1A1A">Red</font>
    * 🟠 `Raznor Obsidian -` <font color="#FFB21A">Orange</font>

### Installation via HACS (Coming Soon)

**This theme is not yet available in HACS.**

## Previews

<p align="center"><a href="https://raw.githubusercontent.com/Raznor09/raznor-obsidian/main/images/blue.png">
  <img alt="Blue theme preview" src="https://raw.githubusercontent.com/Raznor09/raznor-obsidian/main/images/blue.png" width="35%"></a>
  <a href="https://raw.githubusercontent.com/Raznor09/raznor-obsidian/main/images/purple.png">
  <img alt="Purple theme preview" src="https://raw.githubusercontent.com/Raznor09/raznor-obsidian/main/images/purple.png" width="35%"></a>
    <a href="https://raw.githubusercontent.com/Raznor09/raznor-obsidian/main/images/green.png">
  <img alt="Green theme preview" src="https://raw.githubusercontent.com/Raznor09/raznor-obsidian/main/images/green.png" width="35%"></a>
      <a href="https://raw.githubusercontent.com/Raznor09/raznor-obsidian/main/images/red.png">
  <img alt="Red theme preview" src="https://raw.githubusercontent.com/Raznor09/raznor-obsidian/main/images/red.png" width="35%"></a>
        <a href="https://raw.githubusercontent.com/Raznor09/raznor-obsidian/main/images/orange.png">
  <img alt="Orange theme preview" src="https://raw.githubusercontent.com/Raznor09/raznor-obsidian/main/images/orange.png" width="35%"></a>
</p>

## License
This work is licensed under a [Creative Commons Attribution-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-sa/4.0/).
