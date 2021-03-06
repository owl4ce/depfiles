<p align="center">
  <a name="top" href="#octocat-hi-there-thanks-for-visiting-">
     <img alt="owl4ce/dotfiles" height="60%" width="100%" src="https://i.imgur.com/wQ6ih88.png"/>
  </a>
</p>

<p align="center">
  <a href="#cherry_blossom-setup">
    <img width="120px" style="padding: 0 10px;" src="https://i.imgur.com/aRhWQWq.png"/>
  </a>
  <a href="https://github.com/owl4ce/dotfiles/wiki/Keybinds">
    <img width="120px" style="padding: 0 10px;" src="https://i.imgur.com/H62B9tG.png"/>
  </a>
  <a href="https://deviantart.com/owl4ce/gallery/76024204/joyful-desktop-v3">
    <img width="120px" style="padding: 0 10px;" src="https://i.imgur.com/KKkvKE1.png"/>
  </a>
  <a href="#users-configuration">
    <img width="120px" style="padding: 0 10px;" src="https://i.imgur.com/G993TxA.png"/>
  </a>
</p>

##  
### :octocat: Hi there! Thanks for visiting! <img alt="" align="right" src="https://badges.pufler.dev/visits/owl4ce/dotfiles?style=flat-square&label=&color=fa74b2&logo=GitHub&logoColor=white&labelColor=373e4d"/>

<a href="https://github.com/owl4ce/dotfiles/releases/tag/3.2">
  <img src="https://i.imgur.com/4J0aHbi.png" alt="minimal" align="right" width="400px"/>
</a>

This is my **personal configuration** for my favorite openbox window manager and some apps too.

I hope you understand everything here. :wink:

Here are some details about my setup ..
- **Window Manager**               • [Openbox](http://openbox.org/wiki/Main_Page) :art: 4 modes!
- **Shell**                        • [Zsh](https://www.zsh.org) :shell: with [oh-my-zsh](https://github.com/ohmyzsh/ohmyzsh) framework!
- **Terminal**                     • [URxvt](http://software.schmorp.de/pkg/rxvt-unicode.html), [Termite](https://github.com/thestinger/termite) [<kbd>deprecated</kbd>](https://github.com/thestinger/termite#termite-is-obsoleted-by-alacritty)
- **Openbox Menu**                 • [obmenu-generator](https://github.com/trizen/obmenu-generator)
- **Panel**                        • [Tint2](https://gitlab.com/o9000/tint2) :shaved_ice: material icons font!
- **Compositor**                   • [Picom](https://github.com/yshui/picom) :doughnut: rounded corners!
- **Notify Daemon**                • [Dunst](https://github.com/dunst-project/dunst) :leaves: minimalism!
- **Application Launcher**         • [Rofi](https://github.com/davatorium/rofi) :rocket: blazing fast!
- **File Manager**                 • [Thunar](https://github.com/xfce-mirror/thunar) :bookmark: customized sidebar!
- **Music Player**                 • [Ncmpcpp](https://github.com/ncmpcpp/ncmpcpp), [Spotify](https://www.spotify.com/us/download/linux) :rice_scene: riced!
- **GUI Basic-IDE**                • [Geany - The Flyweight IDE](https://www.geany.org)

## :gift: Changelogs <img alt="" align="right" src="https://img.shields.io/github/repo-size/owl4ce/dotfiles?style=flat-square&label=The%20whole%20.files,%20including%20.git%20(branches/tags)&color=cf8ef4&labelColor=373e4d"/>

<a href="https://www.deviantart.com/owl4ce/art/Sakura-Saber-872360153">
  <img src="https://images-wixmp-ed30a86b8c4ca887773594c2.wixmp.com/f/072e191f-a0a5-4be2-bc7a-55eb140b254f/defdpeh-4b226af5-f035-4a5d-aedc-b9417b92563c.png?token=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJzdWIiOiJ1cm46YXBwOiIsImlzcyI6InVybjphcHA6Iiwib2JqIjpbW3sicGF0aCI6IlwvZlwvMDcyZTE5MWYtYTBhNS00YmUyLWJjN2EtNTVlYjE0MGIyNTRmXC9kZWZkcGVoLTRiMjI2YWY1LWYwMzUtNGE1ZC1hZWRjLWI5NDE3YjkyNTYzYy5wbmcifV1dLCJhdWQiOlsidXJuOnNlcnZpY2U6ZmlsZS5kb3dubG9hZCJdfQ.NHrNlWDMbuIVmHkpw4w6l0g7dMJGecLjxXsEPz1tHkI" alt="normal" align="right" width="400px"/>
</a>

<details>
  <summary><strong>v3.0</strong></summary>
  
  - **Visual Mode:**
    - Both modes (minimal) have their own window button styles, margins, sidebar rofi, and dunst layouts.
    - Removed eyecandy tint2 from Joyful Desktop v2
    - Better Tint2 (added temp executor, etc)
    - Added rotation mode (crossover, except minimal mode)

  - **Major Changes:**
    - Removed SLiM sync background, custom slim themes, and unnecessary files/config.
    - All scripts are reproduced all with central variables in one [file](./.owl4ce_var). 
    - Reverse terminal background and foreground (urxvt/termite)
    - Nvim Config - Thanks to [@elenapan](https://github.com/elenapan/dotfiles)
    - SLiM Themes (optional) - See [here](#users-configuration)
    - URxvt Font Resizer - See [keybinds](https://github.com/owl4ce/dotfiles/wiki/Keybinds#urxvt)
    - Included [Networkmanager_dmenu](./.local/bin/networkmanager_dmenu)
    - Oh My ZSH Theme - [Rounded](./.oh-my-zsh/custom/themes/rounded.zsh-theme)
    - Rofi v1.6.0 Supported
    - New Ncmpcpp UI
    - Neofetch Images
    - New Wallpapers
    
</details>

<details>
  <summary><strong>v3.1</strong></summary>
  
  - **Screenshot Script:** Rounded corners, quality, shadows.
  - Terminal UI improvements, particularly font size
  - Bug fixes and improvements
  - Rounded picom as default
  - New Wallpapers
  
</details>

<details>
  <summary><strong>v3.2</strong> <kbd>latest</kbd></summary>
  
  **Major Update:**
  - Customizable partial color accent and start button glyphs - [`L4-L63`](./.owl4ce_var#L4-L63)
  - New ncmpcpp albumart image backend (w3mimgdisplay) - [`L137-L147`](./.owl4ce_var#L137-L147)
  - Centralize dunst and urxvt opacity level and web browser - [`L64-L76`](./.owl4ce_var#L64-L76)
  - Both modes have their own window button last location
  - **Sakura Saber**『桜(さくら)セイバー』 Themed
  - Reconfigure openbox window titlebar colors
  - One click wallpaper generator (colorizer)
  - Auto configure urxvt app icons
  - Notify-send improvements
  - Added **Restart UI**
  - Optimize scripts
  
  For the rest, see the [commits](https://github.com/owl4ce/dotfiles/commits/main). Also check my [workflow](https://youtu.be/kSoViKHt-Yo).
  
</details>
  
## :cherry_blossom: Setup
This is step-by-step how to install these **.files** for automatic setup OpenboxWM custom environment. Just [R.T.F.M](https://en.wikipedia.org/wiki/RTFM).

##  

### Introduction of Linux Rice

<details>
<summary>Please read <a target="_blank" href="https://crispgm.com/page/the-fascinating-arch-linux-rice.html">this</a> and/or <a target="_blank" href="https://jie-fang.github.io/blog/basics-of-ricing">this</a>.</summary>
  
<br>

<p align="center"><a href="#introduction-of-linux-rice"><img src="https://i.redd.it/yu0auhxk5nyz.png" alt="unixporn"/></a></p>

</details>

##  

### Installation (dependencies)
> Customize your choice about dependencies below, this is my complete setup as I use Gentoo/Linux with single OpenboxWM and my preference utility softwares. So, what's in the column is the minimal setup from base-distro installation, everything should be fine without confused screaming, do with your own risk.

> **Detailed environment**  
> Please refer to [wiki/Detailed-Environment](https://github.com/owl4ce/dotfiles/wiki/Detailed-Environment).

> **Warning!**  
> Most configuration contains GNUism using **bash**, **coreutils**, **findutils**, **grep**, **procps-ng**, **psmisc**, and **sed**.
> Assume that you are using [**sudo**](https://www.sudo.ws) or [**doas**](https://github.com/Duncaen/OpenDoas). Want to set up this on top of [**Linux From Scratch**](http://www.linuxfromscratch.org)? :satisfied:

> **Attention!**  
> - [Rofi must be equal version **1.6.x**](https://github.com/owl4ce/dotfiles/issues/37), so for Debian-based you may need to build manually from source.
> - You may want to use `polkit-gnome` instead of `lxsession` (or `lxpolkit`) due to dependency hell.
> - I guess the latest [`yshui/picom`](https://github.com/yshui/picom/issues) might be problematic on certain devices. On me, experiencing some border flickering on the Openbox desktop menu (right click). So I [checkout](https://devopscube.com/checkout-clone-specific-git-commit-id-sha) it on commit **[9cb552e](https://github.com/yshui/picom/commit/9cb552ecd91ec644bf6fcb558ddd44fda5b4f7d9)**.
> - These **.files** fully configured and tested under the **1366**x**768** resolution with **96** DPI, pixels-perfect.

  <details open>
  <summary><strong>Debian & Ubuntu (and all based distributions)</strong></summary>
  
   ```sh
   sudo apt install python psmisc xserver-xorg-core x11-xserver-utils x11-utils imagemagick \
   ffmpeg wireless-tools openbox pulseaudio alsa-utils brightnessctl nitrogen dunst tint2   \
   lxpolkit rxvt-unicode xclip scrot mpd mpc thunar thunar-archive-plugin thunar-volman     \
   ffmpegthumbnailer tumbler w3m w3m-img ncmpcpp viewnior mpv pavucontrol parcellite        \
   gsimplecal neofetch htop xsettingsd xautolock rofi rsync
   ```

  </details>
  
  <details>
  <summary>oh-my-zsh & plugins <kbd>suggested</kbd></summary>
  
   ```sh
   sudo apt install zsh && chsh -s $(command -v zsh)
   sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
   git clone --depth 1 https://github.com/zsh-users/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting
   git clone --depth 1 https://github.com/zsh-users/zsh-autosuggestions.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions
   git clone --depth 1 https://github.com/zsh-users/zsh-completions.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-completions
   ```
    
  </details>
  
  <details>
  <summary>picom</summary>
    
   ```sh
   sudo apt install meson ninja-build libxext-dev libxcb1-dev libxcb-damage0-dev libxcb-xfixes0-dev        \
   libxcb-shape0-dev libxcb-render-util0-dev libxcb-render0-dev libxcb-randr0-dev libxcb-composite0-dev    \
   libxcb-image0-dev libxcb-present-dev libxcb-xinerama0-dev libxcb-glx0-dev libpixman-1-dev libdbus-1-dev \
   libconfig-dev libgl1-mesa-dev libpcre2-dev libpcre3-dev libevdev-dev uthash-dev libev-dev libx11-xcb-dev
   ```
   ```sh
   git clone https://github.com/yshui/picom.git          && \
   cd picom/ && git submodule update --init --recursive  && \
   git checkout 9cb552ecd91ec644bf6fcb558ddd44fda5b4f7d9 && \
   meson --buildtype=release . build                     && \
   ninja -C build                                        && \
   ninja -C build install
   ```

  </details>

  <details>
  <summary>obmenu-generator</summary>
  
   > I haven't tested it yet.
  
   - [Install the **.deb** package](https://software.opensuse.org/download.html?project=home%3AHead_on_a_Stick%3Aobmenu-generator&package=obmenu-generator);
   - [Build manually from source](https://github.com/trizen/obmenu-generator/blob/master/INSTALL.md).
  
  </details>
  
  <br>
  
  <details open>
  <summary><strong>Arch Linux (and all based distributions)</strong></summary>
  
   > Ensure your **AUR Helper** is [paru](https://github.com/Morganamilo/paru) or [yay](https://github.com/Jguer/yay).
  
   ```sh
   paru -S python psmisc xorg-server xorg-xrandr xorg-xprop xorg-xwininfo imagemagick \
   ffmpeg wireless_tools openbox pulseaudio pulseaudio-alsa alsa-utils brightnessctl  \
   nitrogen dunst tint2 lxsession rxvt-unicode-truecolor-wide-glyphs xclip scrot mpd  \
   mpc thunar thunar-archive-plugin thunar-volman ffmpegthumbnailer tumbler w3m       \
   ncmpcpp viewnior mpv pavucontrol parcellite gsimplecal neofetch htop xsettingsd    \
   xautolock obmenu-generator perl-gtk3 picom-git rofi rsync
   ```

  </details>
  
  <details>
  <summary>oh-my-zsh & plugins <kbd>suggested</kbd></summary>
  
   ```sh
   sudo pacman -S zsh && chsh -s $(command -v zsh)
   sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
   git clone --depth 1 https://github.com/zsh-users/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting
   git clone --depth 1 https://github.com/zsh-users/zsh-autosuggestions.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions
   git clone --depth 1 https://github.com/zsh-users/zsh-completions.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-completions
   ```
  
  </details>

  <br>
  
  <details>
  <summary><strong>Another Linux Distribution</strong></summary>
  
   Customize/port dependencies yourself!  
   
   **For example,**  
   - [Gentoo/Linux](https://packages.gentoo.org)  
     *[See owl4ce's portage configuration](https://github.com/owl4ce/hmg/tree/main/etc/portage).*
     
   - [Void (Linux)](https://voidlinux.org/packages)
   
   > You can reference the package names with Arch Linux.  
   > For Gentoo/Linux, I recommend to enabling [keywords](https://wiki.gentoo.org/wiki/ACCEPT_KEYWORDS) for specific packages or using [live ebuild](https://wiki.gentoo.org/wiki/Ebuild).
  
   If it's not there, build it manually from git source code or from elsewhere.
  
  </details>
  
  <br>
    
  **Optional:**  
  [geany](https://geany.org) + [plugins](https://plugins.geany.org), [gimp](https://www.gimp.org), [inkscape](https://inkscape.org), [nano](https://www.nano-editor.org) + [syntax highlighting](https://github.com/scopatz/nanorc), [nm-applet](https://gitlab.gnome.org/GNOME/network-manager-applet), [spotify](https://www.spotify.com/us/download/linux) + [playerctl](https://github.com/altdesktop/playerctl), [xfce4-power-manager](https://docs.xfce.org/xfce/xfce4-power-manager/getting-started).
  
##  

### Installation (dotfiles) 
  
  > **Are all directories required?** :thinking:  
  > Please refer to [wiki/Detailed-Environment](https://github.com/owl4ce/dotfiles/wiki/Detailed-Environment).
  
  <details open>
  <summary><strong>Most of .files</strong></summary>
   
   You can clone or download as an [archive](https://github.com/owl4ce/dotfiles/releases). After that, put all files in the **dotfiles** folder into user's home directory.
   > Assume you are cloning this in the `~/Documents` directory for example. I recommend to install with **rsync**.
   ```sh
   cd ~/Documents/ && git clone --depth 1 https://github.com/owl4ce/dotfiles.git
   ```
   ```sh
   rsync -avxHAXP --exclude '.git*' --exclude 'LICENSE' --exclude '*.md' dotfiles/ ~/
   ```
   > **Warning!**  
   > Ensure the rsync command must be correct as above.
   > 
   > **Explanation**
   > | Options     | Function                                            |
   > |:-----------:|-----------------------------------------------------|
   > | `-a`        | all files, with permissions, etc..                  |
   > | `-v`        | verbose, mention files                              |
   > | `-x`        | stay on one file system                             |
   > | `-H`        | preserve hard links (not included with -a)          |
   > | `-A`        | preserve ACLs/permissions (not included with -a)    |
   > | `-X`        | preserve extended attributes (not included with -a) |
   > | `-P`        | show progress                                       |
   > | `--exclude` | exclude files matching PATTERN                      |
   >
   > **Differences**  
   > - `cp` is for duplicating stuff and by default only ensures files have unique full path names.
   > - `rsync` is for synchronising stuff and uses the size and timestamp of files to decide if they should be replaced. It has many more options and capabilities than **cp**.
   >
   >   
   > I recommend to not deleting the **dotfiles** directory after cloning to make upgrades easier. Read the [update](#update).
   
  </details>
  
  <details open>
  <summary><strong>Icons</strong></summary>
    
   > `pushd` is same as `cd`, but can return back to the previous directory by using `popd` (checkpoint).
   ```sh
   pushd ~/.icons/ && \
       tar -xJf Papirus-Custom.tar.xz && tar -xJf Papirus-Dark-Custom.tar.xz && \
       sudo ln -vs ~/.icons/Papirus-Custom /usr/share/icons/
       sudo ln -vs ~/.icons/Papirus-Dark-Custom /usr/share/icons/
   popd
   ```
   > **Why I need to link icons to [/usr](https://tldp.org/LDP/Linux-Filesystem-Hierarchy/html/usr.html)?** :thinking:  
   > That's needed by dunst in order to display most of icon from notification that spawned by programs.
   > 
   > **Optionally,**  
   > You can delete the tarball achives after extracting.
   
  </details>
  
  <details open>
  <summary><strong>Refresh Font Cache</strong></summary>
   
   ```sh
   fc-cache -rv
   ```
   
  </details>
  
  <details open>
  <summary><strong>Update MPD Database</strong></summary>
   
   ```sh
   [ -n "$(pgrep mpd)" ] || mpd && mpc update
   ```
   
  </details>
  
  <details open>
  <summary><strong>Root Privileges with <a href="https://en.wikipedia.org/wiki/Setuid#SUID">SUID</a></strong></summary>
   
   - `brightnessctl`
   - *others if needed.*
   
   > ~For **brightnessctl**, I would recommend [adding users to video group](https://wiki.archlinux.org/index.php/Users_and_groups#Group_management).~  
   > I don't think this is necessary since **brightnessctl** has (systemd-)udev rules.
   
   ```sh
   sudo chmod u+s $(command -v brightnessctl)
   ```
   
  </details>
  
### The step you are waiting for
The final step is login into **openbox-session**, basically login from your display manager like lightdm, gdm, etc.

> Ensure `sh` is symlink to `bash`, as it's uses [bashism](https://mywiki.wooledge.org/Bashism). **Why bash?** Simple, it's **bloated** but **powerful**.
> ```sh
> [ "$(readlink -f /bin/sh)" != "$(command -v bash)" ] && sudo ln -vfs $(command -v bash) /bin/sh
> ```

If you are using `~/.xinitrc` without display manager, simply add the following one-liner commands at the end.

**Systemd-based Linux Distribution**  
```sh
exec openbox-session
```

**[Init-Freedom](https://www.devuan.org/os/init-freedom) Linux Distribution**  
```sh
exec dbus-launch --exit-with-session openbox-session
```

Then you can proceed to [user's configuration](#users-configuration). Explore!

##  

### Additional

**Suggested replacement commands**
- `ls` ➜ [`exa`](https://github.com/ogham/exa)  

[`~/.zshrc`](./.zshrc#L137-L138)  
```zsh
...

137 alias ls="exa -lgh --icons --group-directories-first"
138 alias la="exa -lgha --icons --group-directories-first"

...
```

- `cat` ➜ [`bat`](https://github.com/sharkdp/bat)

- [See more](https://github.com/ibraheemdev/modern-unix).

<br>

**Suggestion for tiling users**
<p align="center">
  <a href="https://github.com/blrsn/zentile">
    <img src="https://raw.githubusercontent.com/blrsn/zentile/master/docs/zentile-logo.png" alt=""/>
  </a>
</p>

I recommend to build it from source. Then put the **zentile** binary into your **PATH**, for example in `~/.local/bin/`.
```sh
# To run in the background (detached)
zentile &! 

# To kill (or pkill)
killall zentile
```

##  

### Update

Since I recommend using **rsync** from start, the easiest way is to list the files that will not be updated to avoid replacing personal files with files in the **dotfiles**. First, update the local repository with remote git repository.
> Remember where you cloned this repository. From the start we assumed that it was in `~/Documents`.
```sh
cd ~/Documents/ && \
pushd dotfiles/ && git pull --unshallow && popd
```
Then create a file with **PATTERN** list containing files/dirs that **rsync** will exclude. For example,  
`~/.dotexc`
```cfg
.git*
LICENSE
*.md
*.joy
geany
GIMP
gtk-3.0
config.conf
autostart
environment
tray
shared
sidebar
termite
Thunar
xfconf
zathura
.fonts
.nothing
.mpd
.gtkrc-2.0
.zshrc
.nanorc
.Xresources
.xsettingsd
```
> Use `find` command to check the **PATTERN**,
> ```sh
> find dotfiles/ -iname 'PATTERN'
> ```
.. and whatever the file is. Sync now!
```sh
rsync -avxHAXP --exclude-from ~/.dotexc dotfiles/ ~/
```

##  

### User's configuration
- **About XDG user directories and Thunar-specific <kbd>tips</kbd>**
   > If you just installed Thunar without XFCE, you might get sidebar without XDG directories like **Documents**, **Downloads**, etc. After you generate those directories, open Thunar then select or block the directories, right-click and click **Send To** 🡲 **Side Pane**. Read XDG user directories at [ArchWiki](https://wiki.archlinux.org/title/XDG_user_directories).
   > 
   > If you want to get 100% Thunar looks similar to my screenshot, ensure to copy my Thunar configuration. Then hide **Computer**, **Desktop**, **Recent** or whatever you want by right-clicking on **Places** in the Thunar side pane. By default, my Thunar side pane configuration uses simple 16px icons.
   
- **SLiM Themes <kbd>deprecated, optional</kbd>**
  <details>
  <summary><strong>See</strong></summary>
  
    <p align="center">In fact, I use SLiM just for lockscreen <b>@ 2020</b>. Currently, I don't use any lockscreen.</p>
    
    <p align="center"><a href="https://www.deviantart.com/owl4ce/art/Floflo-Batik-SLiM-Themes-861519439">
      <img src="https://images-wixmp-ed30a86b8c4ca887773594c2.wixmp.com/f/072e191f-a0a5-4be2-bc7a-55eb140b254f/de8xcnj-d1413505-68ee-49bd-ba72-00cd3f2a2d9e.png?token=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJzdWIiOiJ1cm46YXBwOiIsImlzcyI6InVybjphcHA6Iiwib2JqIjpbW3sicGF0aCI6IlwvZlwvMDcyZTE5MWYtYTBhNS00YmUyLWJjN2EtNTVlYjE0MGIyNTRmXC9kZTh4Y25qLWQxNDEzNTA1LTY4ZWUtNDliZC1iYTcyLTAwY2QzZjJhMmQ5ZS5wbmcifV1dLCJhdWQiOlsidXJuOnNlcnZpY2U6ZmlsZS5kb3dubG9hZCJdfQ.KPhW15Vepsxlr7San7OuBA_oyVfs-k7Bh1hCrbqC528" alt="floflo-batik" align="center"/>
    </a></p>
    
    <p align="center">Just click on the image above!</p>
    
  </details>

- **Chromium-based Web Browser <kbd>suggested</kbd>**
  <details>
  <summary><strong>See</strong></summary>
  
    **Settings:** [`chrome://settings/`](chrome://settings/)
    - **Themes:** `Use GTK+`
    - `Use system title bar and borders`
    
    <br>
    
    <p align="center"><a href="https://brave.com/"><img src="https://i.imgur.com/JYVvCLp.png" alt="brave.thumbnail"/></a></p>
    
    <p align="center">You may want to turn on <a href="https://www.linuxuprising.com/2021/01/how-to-enable-hardware-accelerated.html">Hardware Acceleration</a>. See also <a href="https://gist.github.com/ibLeDy/1495735312943b9dd646fd9ddf618513">recommended flags</a>.</p>
    
  </details>
  
- **Spotify - Spicetify Theme <kbd>suggested</kbd>**
  <details>
  <summary><strong>See</strong></summary>
  
    <br>
    
    <p align="center"><a href="https://github.com/owl4ce/spicetify-themes/tree/new/Dribbblish#eyecandy">
    <img src="https://raw.githubusercontent.com/owl4ce/spicetify-themes/new/Dribbblish/eyecandy.png" alt="spicetify.dribbblish-eyecandy"/>
    </a></p>
    <p align="center"><a href="https://github.com/owl4ce/spicetify-themes/tree/new/Dribbblish#mechanical">
    <img src="https://raw.githubusercontent.com/owl4ce/spicetify-themes/new/Dribbblish/mechanical.png" alt="spicetify.dribbblish-mechanical"/>
    </a></p>
    
    <p align="center">Just click on the image above!</p>
    <p align="center">Or maybe you want a <a href="https://downgit.github.io/#/home?url=https://github.com/owl4ce/spicetify-themes/tree/new/Dribbblish">direct link</a> without downloading the complete repository.</p>
    <p align="center">??? <a href="https://github.com/abba23/spotify-adblock">spotify-adblock</a> ???</p>
    <p align="center">??? <a href="https://github.com/tsmetana/spotify-tray">spotify-tray</a> ???</p>
    
  </details>
  
- **Telegram Desktop <kbd>suggested</kbd>**
  <details>
  <summary><strong>See</strong></summary>
  
    <br>
    
    <p align="center"><a href="https://github.com/gilbertw1/telegram-nord-theme">
    <img src="https://i.imgur.com/5jEGp1j.png" alt="tdesktop.nord"/>
    </a></p>
    
    <p align="center">Just click on the image above!</p>
    
  </details>
    
- **Capitaine Cursors Theme <kbd>suggested</kbd>**
  <details>
  <summary><strong>See</strong></summary>
  
    <br>
    
    <p align="center"><a href="https://www.pling.com/p/1148692">
    <img src="https://cdn.pling.com/img/6/8/5/6/0e64785edeb13cf2527cb2fd0f29774af6c4.png" alt="capitaine-cursors"/>
    </a></p>
    <p align="center"><a href="https://www.pling.com/p/1148692">
    <img src="https://cdn.pling.com/img/4/8/3/5/e6df21a4d723a4e21a1b85f9ae5979f6fb25.png" alt="capitaine-cursors"/>
    </a></p>
    
    <p align="center">Just click on the image above!</p>
    
  </details>
  
- **Touchpad tap-to-click (libinput) <kbd>optional</kbd>**  
  `/etc/X11/xorg.conf.d/30-touchpad.conf`
  ```cfg
  Section "InputClass"
      Identifier "touchpad"
      Driver "libinput"
      MatchIsTouchpad "on"
      Option "Tapping" "on"
      Option "TappingButtonMap" "lmr"
  EndSection
  ```
  [More information](https://wiki.archlinux.org/index.php/Libinput).
  
- **User's Preferences <kbd>required</kbd>**  
  [`~/.owl4ce_var`](./.owl4ce_var)  
  > Manage all your settings there. I hope all comments there are easy to understand. ^^
  
- **User's Tray Icons**  
  [`~/.config/openbox/tray`](./.config/openbox/tray)  
  > An example is turning on `nm-applet`, by default I don't use it and use [`networkmanager_dmenu`](./.local/bin/networkmanager_dmenu) instead.
  > 
  > > **How about battery indicator?**  
  > > Because on the `tint2` panel I turned off battery status. Alternatively, install `xfce4-power-manager` and enable system tray icon in the **xfce4-power-manager-settings**.
  > 
  > Remove hashtags as your needs, then re-login the openbox-session. Should be fine without confusion.
  > > Putting commands here means when switching Visual Mode, all those programs will be restarted.
  ```cfg
  1 #
  2 # This tray will restart after switching modes
  3 # Please add "&" after command
  4 #
  5 # ---
  6
  7 parcellite &
  8 #nm-applet &
  9 #xfce4-power-manager &
  ```
  
- **Available Default Apps**  
  [` ~/.scripts/default-apps/list.joy`](./.scripts/default-apps/list.joy)
  > - **Terminal:** `urxvt` `termite`
  > - **Lockscreen:** *anything*
  > - **Music Player:** `mpd` `spotify`
  > - **File Manager:** *anything*
  ```cfg
  1 terminal="urxvt"
  2 lockscreen="slimlock"
  3 musicpl="mpd"
  4 filemanager="thunar"
  ```
  > Termite is now [obsolete](https://github.com/thestinger/termite#termite-is-obsoleted-by-alacritty).
  
- **MPD Music Directory**  
  [`~/.mpd/mpd.conf`](./.mpd/mpd.conf#L6)
  ```cfg
  ...
  
  6 music_directory     "~/Music"
  
  ...
  ```
  
- **Ncmpcpp Music Directory**  
  > Auto-connect with MPD.
  > 
  > **How to use ncmpcpp album-art?**  
  > It's easy, just put `(album|cover|folder|artwork|front).(jpe?g|png|gif|bmp)` into folder with song album. Recommended image size is *500px* ( **1:1** ) or more. This is only for URxvt. [See keybinds](https://github.com/owl4ce/dotfiles/wiki/Keybinds#ncmpcpp).

- **Audio Server <kbd>optional</kbd>**  
  [`~/.config/openbox/autostart`](./.config/openbox/autostart#L9)  
  <details>
  <summary>This is optional for Linux distributions that don't use systemd as their init.</summary>
  
  - **Pulseaudio**
    ```sh
    ...

    9  # There was once a pulseaudio here.
    10 pulseaudio --start --log-target=syslog 2>/dev/null &

    ...
    ```
    
    Or if you use [pipewire](https://github.com/PipeWire/pipewire) as pulseaudio.
  - **Pipewire as Pulseaudio**
    > More details at [ArchWiki](https://wiki.archlinux.org/index.php/PipeWire#PulseAudio_clients) / [Gentoo Wiki](https://wiki.gentoo.org/wiki/Pipewire#Replacing_PulseAudio). Ensure `pulseaudio` is uninstalled or disable **autospawn**.  
    > `/etc/pulse/client.conf`
    > ```cfg
    > ...
    >
    > 25  autospawn = no
    >
    > ...
    > ```
    
    ```sh
    ...

    9  # There was once a pulseaudio here.
    10 pipewire 2>/dev/null &
    
    ...
    ```
    
  </details>
  
- **Neofetch Image Source**  
  [`~/.config/neofetch/config.conf`](./.config/neofetch/config.conf#L641-L665)
  ```cfg
  ...
  
  641 # Image Source
  642 #
  643 # Which image or ascii file to display.
  644 #
  645 # Default:  'auto'
  646 # Values:   'auto', 'ascii', 'wallpaper', '/path/to/img', '/path/to/ascii', '/path/to/dir/'
  647 #           'command output (neofetch --ascii "$(fortune | cowsay -W 30)")'
  648 # Flag:     --source
  649 #
  650 # NOTE: 'auto' will pick the best image source for whatever image backend is used.
  651 #       In ascii mode, distro ascii art will be used and in an image mode, your
  652 #       wallpaper will be used.
  653 #image_source="auto"
  654 #image_source="${HOME}/.config/neofetch/images/arch.png"
  655 #image_source="${HOME}/.config/neofetch/images/arch_dark.png"
  656 #image_source="${HOME}/.config/neofetch/images/artix.png"
  657 #image_source="${HOME}/.config/neofetch/images/bedrock.png"
  658 #image_source="${HOME}/.config/neofetch/images/gentoo.png"
  659 #image_source="${HOME}/.config/neofetch/images/gentoo_dark.png"
  660 #image_source="${HOME}/.config/neofetch/images/lofi.png"
  661 image_source="${HOME}/.config/neofetch/images/sakura.png"
  662 #image_source="${HOME}/.config/neofetch/images/ubuntu.png"
  663 #image_source="${HOME}/.config/neofetch/images/ubuntu_dark.png"
  664 #image_source="${HOME}/.config/neofetch/images/void.png"
  665 #image_source="${HOME}/.config/neofetch/images/void_dark.png"
  
  ...
  ```
  <details>
  <summary><strong>See Images</strong></summary>
  
  Arch|Gentoo|Ubuntu|Void
  |----|----|----|----|
  ![Arch](./.config/neofetch/images/arch.png)|![Gentoo](./.config/neofetch/images/gentoo.png)|![Ubuntu](./.config/neofetch/images/ubuntu.png)|![Void](./.config/neofetch/images/void.png)

  Arch Dark|Gentoo Dark|Ubuntu Dark|Void Dark
  |----|----|----|----|
  ![Arch](./.config/neofetch/images/arch_dark.png)|![Gentoo](./.config/neofetch/images/gentoo_dark.png)|![Ubuntu](./.config/neofetch/images/ubuntu_dark.png)|![Void](./.config/neofetch/images/void_dark.png)

  Artix|LoFi|Bedrock
  |---|---|---|
  ![Artix](./.config/neofetch/images/artix.png)|![LoFi](./.config/neofetch/images/lofi.png)|![Bedrock](./.config/neofetch/images/bedrock.png)
  
  <table border="0"
  <tr>
  <td>
    <b>Sakura</b>
  </tr>
  </td>
  <tr>
  <td>
  <br>
    <p align="center"><img src="./.config/neofetch/images/sakura.png" alt="Sakura"/></p>
  </td>
  </tr>
  </table>
  
  </details>

## :memo:  Notes
### <p align="center">Color Schemes</p>
<p align="center"><a href="#color-schemes"><img src="https://i.imgur.com/QEUTWUe.png" alt="owl4ce.color-schemes" height="60%" width="100%"></a></p>

<p align="center">© <a href="https://github.com/owl4ce">owl4ce</a> - <a href="https://www.nordtheme.com">Nord Color Palette-compatible</a></p>

<table border="0">
<tr>
<td>
<br>
<p align="center">:speech_balloon:</p>
</td>
</tr>
<tr>
<td>
<br>
<p align="center"><b>Widget?</b> We don't do that here. My main philosophy in building this is as a minimal replacement for Desktop Environment without any desktop decoration e.g icons and widgets, but it can be adapted to taste of user with an overall theme based on one color palette and can be easily switched between Mechanical-Eyecandy. I admit, the downside is that it relies heavily on the GNU/Linux operating system since GNUism is not POSIX-compliant (portability with other OSs). Most of the size of this repository is large due to wallpapers, icons, and git caches.</p><p align="center">Please don't underrate, I've configured them all since April 2020 and have been stuDYING them since <a href="https://github.com/owl4ce/dotfiles/wiki/My-Linux-Ricing-Journey">October 2019</a>. Awesome open-source. If you support it, <b>star</b> it or make a <a href="https://github.com/owl4ce/dotfiles/pulls">PR</a>. Or if there is a problem with configuration (please check previous issues if any) you can make an <a href="https://github.com/owl4ce/dotfiles/issues">issue</a> here. Also if you want a <a href="https://github.com/owl4ce/dotfiles/discussions">discussion</a>.</p><p align="center"><b>Thank You!</b></p><p align="center"> Feel free to modify, under <a href="./LICENSE">GPL-3.0</a> except for GTK+ themes, gladient icons, fonts, and wallpapers.</p><p align="center"><b>Why openbox?</b> Really a perfect next-gen window manager, easily configurable, and less resources usage.</p><p align="center">Openbox isn't dead, but completed features.</p>
</td>
</tr>
<tr>
<td>
<br>
<a href="https://starchart.cc/owl4ce/dotfiles"><p align="center"><img src="https://starchart.cc/owl4ce/dotfiles.svg"/></p></a>
</td>
</tr>
</table>

<br>

## :gift_heart:  Tip Jar
If you enjoy my **dotfiles** and would like to show your appreciation, you may want to tip me here.
It's never required but always wholeheartedly appreciated.

Thank you from the bottom of my heart! :heartpulse:

[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/V7V05ZACS)
[![liberapay](https://liberapay.com/assets/widgets/donate.svg)](https://liberapay.com/owl4ce/donate)

* **BTC:** `3DrjWyd6Xgv4tKoL56mPtoQX4fL4LbR7zf`
* **ETH:** `0x818fC9B82548C1020ed7370DFeb04BCbADc59191`

<br>

## :confetti_ball:  Acknowledgements
- **Inspiration and main resources**
  - [Elena](https://github.com/elenapan)
  - [Adhi Pambudi](https://github.com/addy-dclxvi)
  - [Fikri Omar](https://github.com/fikriomar16)
  - [Rizqi Nur Assyaufi](https://github.com/bandithijo)
  - [Muktazam Hasbi Ashidiqi](https://github.com/reorr)
  - [Galih Wisnuaji](https://github.com/nekonako)
  - [Ghani Rafif](https://github.com/ekickx)
  - [Nanda Oktavera](https://github.com/okitavera)
  - [Aditya Shakya](https://github.com/adi1090x)
  - [Dylan Araps](https://github.com/dylanaraps)
  - ?

- **Extended resources or the manual**
  - [Digital Synopsis](https://digitalsynopsis.com);
  - [Openbox Wiki](http://openbox.org/wiki/Help:Themes);
  - [Gnome Pango Markup](https://developer.gnome.org/pango/stable/pango-Markup.html);
  - [Custom Environment at ArchWiki](https://wiki.archlinux.org/index.php/desktop_environment#Custom_environments);
  - [Recommended Applications at Gentoo Wiki](https://wiki.gentoo.org/wiki/Recommended_applications);
  - [Pure Bash Bible](https://github.com/dylanaraps/pure-bash-bible);
  - [Stark's Color Scripts](https://github.com/stark/Color-Scripts);
  - [notify-send.sh (bash)](https://github.com/vlevit/notify-send.sh);
  - [networkmanager-dmenu (python3)](https://github.com/firecat53/networkmanager-dmenu);
  - [URxvt Manual](https://linux.die.net/man/1/urxvt);
  - [URxvt Resize-Font](https://github.com/simmel/urxvt-resize-font);
  - [URxvt Tabbed-Extended](https://github.com/mina86/urxvt-tabbedex);
  - [Showing Album Cover in Ncmpcpp](https://marcocheung.wordpress.com/2015/08/09/showing-album-cover-in-ncmpcpp);
  - [Complete List of GitHub Markdown Emoji Markup](https://gist.github.com/rxaviers/7360908);
  - Most people on some GNU/Linux and UN*X forums.
  
- **Contributors**
  - [Ekaunt](https://github.com/ekaunt) - [Better promptmenu](https://github.com/owl4ce/dotfiles/pull/2)
  - [HopeBaron](https://github.com/HopeBaron) - [Termite config](https://github.com/owl4ce/dotfiles/pull/4)
  - [Justin Faber](https://github.com/vredesbyyrd) - [Rofi matched lines indicator](https://github.com/owl4ce/dotfiles/issues/33#issuecomment-753399179)
  - [Vcyzteen](https://github.com/vcyzteen) - [URxvt copy-paste](https://github.com/owl4ce/dotfiles/pull/67/files#diff-76ca8b85960fd14348e9caa3ebabe00c3cf21593a94036f4ba3305c262809a34R59-R60)
  
    <br>
    <a href="https://github.com/owl4ce/dotfiles/graphs/contributors">
      <img src="https://contrib.rocks/image?repo=owl4ce/dotfiles" />
    </a>

    Made with [contributors-img](https://contrib.rocks).
  
- **Softwares**
  - [Geany - The Flyweight IDE](https://www.geany.org);
  - [GIMP - GNU Image Manipulation Program](https://www.gimp.org);
  - [Gpick - Advanced Color Picker](http://www.gpick.org);
  - [Gucharmap - GNOME Character Map](https://wiki.gnome.org/Apps/Gucharmap);
  - [Themix - GUI Theme Designer](https://github.com/themix-project/oomox);
  - Tint2conf, etc.

- **Our local linux community [Linuxer Desktop Art](https://facebook.com/groups/linuxart) and [@dotfiles_id](https://t.me/dotfiles_id), also the great [r/unixporn](https://www.reddit.com/r/unixporn).**
- **© All artists who create icons, illustrations, and wallpapers.**
  
  The original source I've found:
  - [Gladient Icons](https://play.google.com/store/apps/details?id=com.maxghani.gladient)
  - [桜](https://www.pixiv.net/en/artworks/80518034)
  - [桜セイバー沖田総司](https://www.pixiv.net/en/artworks/59740059)
  - [沖田総司](https://www.pixiv.net/en/artworks/62996457)
