# Raznor Obsidian theme for Home Assistant
<p align="left">
  <a href="https://github.com/hacs/default" target="_blank"><img src="https://img.shields.io/badge/HACS-Default-53b3ff.svg?style=for-the-badge" alt="HACS Default"></a>
  <a href="https://github.com/Raznor09" target="_blank"><img src="https://img.shields.io/badge/GitHub-Raznor09-7e1ab2?style=for-the-badge&logo=github" alt="Raznor09 on GitHub"></a>
  <a href="https://github.com/Raznor09/raznor-obsidian/releases/latest" target="_blank"><img src="https://img.shields.io/github/v/release/Raznor09/raznor-obsidian?style=for-the-badge&label=Release&color=1ab21a" alt="GitHub Release"></a>
  <a href="https://github.com/Raznor09/raznor-obsidian/releases" target="_blank"><img src="https://img.shields.io/github/downloads/Raznor09/raznor-obsidian/total?style=for-the-badge&color=ff1a1a" alt="Total Downloads"></a>
  <a href="https://coff.ee/raznor09" target="_blank"><img src="https://img.shields.io/badge/COFFEE-ffb21a?style=for-the-badge&label=BUY%20ME%20A" alt="Buy me a coffee"></a>
</p>
  
- A clean, all-black theme with multiple color variants, designed for a minimalist and modern look.
- This single file provides several pre-configured color options, including 🔵Blue, 🟣Purple, 🟢Green, 🔴Red and 🟠Orange.

---

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

---

### Set Theme as Default for all Devices

To apply the selected Raznor Obsidian theme as the default for all devices accessing your Home Assistant instance, follow these steps:

1.  Open **Developer Tools** in Home Assistant.
2.  Go to the **Actions** tab.
3.  Search for `frontend.set_theme` (or "Set the default theme").
4.  Under **Theme**, select your desired Raznor Obsidian theme (e.g., `Raznor Obsidian - Blue`).
5.  The 'Mode' field is not required for this action.
6.  Click on **Perform Action**.

---

### Installation via HACS (Coming Soon)

**This theme is not yet available in HACS.**

---

## Support the Project

This theme is maintained with great pleasure. If you appreciate this theme and would like to support my work, please consider a small donation. Every contribution is highly valued!

<a href="https://coff.ee/raznor09" target="_blank" rel="noreferrer noopener"><img src="https://cdn.buymeacoffee.com/buttons/v2/default-blue.png" alt="Buy Me A Coffee" width="150px"></a>

---

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

---

## License
This work is licensed under a [Creative Commons Attribution-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-sa/4.0/).

---

## Credits
This theme is based on the [Google Theme by JuanMTech](https://github.com/JuanMTech/google-theme).
All credits for the original integration go to [JuanMTech](https://github.com/JuanMTech).
