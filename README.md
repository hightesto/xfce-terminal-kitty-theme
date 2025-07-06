# xfce-terminal-kitty-theme ![image](https://github.com/user-attachments/assets/beab7b2d-4312-442a-add8-3c56448e5500)
A theme for kitty based on the colors of Xfce4-terminal

## Installation

1. Download the theme
      ```bash
      THEME=https://raw.githubusercontent.com/hightesto/xfce-terminal-kitty-theme/master/themes/xfce-terminal-kitty-theme.conf
      wget "$THEME" -P ~/.config/kitty/kitty-themes/themes
      ```

2. Choose a theme and create a symlink:

    ```bash
    cd ~/.config/kitty
    ln -s ./kitty-themes/themes/xfce-terminal-kitty-theme.conf ~/.config/kitty/theme.conf
    ```

3. Add this line to your kitty.conf configuration file:

    ```
    include ./theme.conf
    ```
