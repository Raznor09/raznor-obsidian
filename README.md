# Raznor Obsidian Theme for Home Assistant

A clean, all-black theme with multiple color variants, designed for a minimalist and modern look. This single file provides several pre-configured color options, including Blue, Purple, Green, and Red.

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
5.  Then, go to your Profile page and select `Raznor Obsidian - Blue`, `Raznor Obsidian - Purple`, `Raznor Obsidian - Green`,  `Raznor Obsidian - Red` or `Raznor Obsidian - Orange`, from the Theme dropdown.

### Installation via HACS (Coming Soon)

This theme is not yet available in HACS.

## License
This work is licensed under a [Creative Commons Attribution-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-sa/4.0/).
