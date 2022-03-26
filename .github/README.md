<!-- Screenshot -->
<div align="center">
    <img src="https://awesomewm.org/images/awesome-logo.svg">
</div>

<br>

<div align="center">
    <img src="assets/awesome.png">
</div>

<br>
<br>

<a href="https://awesomewm.org/"><img alt="AwesomeWM Logo" height="160" align = "left" src="https://awesomewm.org/doc/api/images/AUTOGEN_wibox_logo_logo_and_name.svg"></a>
<b>  AwesomeWM Dotfiles  </b>

Welcome to my AwesomeWM configuration files! 

so yeah now i'm using awesomewm, looks like i'll be use this wm forever.

Because only this wm can satisfy me.

Fyi, I use night colorscheme, and it's so beautiful.

These dotfiles are made with love.

<h2></h2><br>

**Here are some details about my setup:**

| Programs   | Using             |
| ---------- | ----------------- |
| WM         | awesome-git       |
| OS         | arch linux        |
| Terminal   | alacritty         |
| Shell      | zsh               |
| Editor     | neovim / vscode   |
| Compositor | picom             |
| Launcher   | rofi              |

<h2></h2><br>

<details open>
<summary><strong>S E T U P</strong></summary>

1. Install dependencies

   + Dependencies

     - **Arch Linux** (and all Arch-based distributions)

         *Assuming your AUR helper is* `yay`

         ```shell
         yay -S awesome-git picom-jonaburg-git alacritty rofi todo-bin acpi acpid \
         wireless_tools jq inotify-tools polkit-gnome xdotool xclip maim \
         brightnessctl alsa-utils alsa-tools pulseaudio lm_sensors \
         mpd mpc mpdris2 ncmpcpp playerctl --needed 
         ```


2. Install needed fonts

   You will need to install a few fonts (mainly icon fonts) in order for text and icons to be rendered properly.

   Necessary fonts:
   + **Iosevka**  - [here](https://github.com/ryanoasis/nerd-fonts/)
   + **Icomoon**  - [here](https://www.dropbox.com/s/hrkub2yo9iapljz/icomoon.zip?dl=0)
   + **Material** - [here](https://github.com/google/material-design-icons)

   Once you download them and unpack them, place them into `~/.fonts` or `~/.local/share/fonts`.
  
3. Install my AwesomeWM configuration files

    > Clone this repository

   ```shell
   git clone https://github.com/rxyhn/AwesomeWM-Dotfiles.git
   cd AwesomeWM-Dotfiles
   ```

    > Copy config and binaries files

   ```shell
    cp -r ./config/* ~/.config/
    cp -r ./bin/* ~/.local/bin/
    cp -r ./misc/. ~/
   ```

4. Lastly, log out from your current desktop session and log in into AwesomeWM.

</details>

<br>

<details open>
<summary><strong>F E A T U R E S</strong></summary>

<b>These are the features included in my AwesomeWM setups!</b>

   + Aesthetic `Dashboard` ngl.
   + Notification Center
   + Control Panel
   + ToDo Reminder
   + Battery Indicator
   + PopUp Notifications
   + Applications Launcher
   + Custom mouse-friendly `ncmpcpp` UI with album art ofc.
   + Word Clock Lockscreen with PAM Integration
   + Some Tooltip Widget
   + Hardware Monitor
   + Beautiful `colorscheme` ikr.

</details>
<br>
<br>

## Acknowledgements

   - **Special thanks to**
      + [ner0z](https://github.com/ner0z)
      + [ChocolateBread799](https://github.com/ChocolateBread799)
      + [JavaCafe01](https://github.com/JavaCafe01)

<br>
<br>

<p align="center"><a href="https://github.com/rxyhn/AwesomeWM-Dotfiles/blob/main/.github/LICENSE"><img src="https://img.shields.io/static/v1.svg?style=flat-square&label=License&message=GPL-3.0&logoColor=eceff4&logo=github&colorA=061115&colorB=67AFC1"/></a></p>
