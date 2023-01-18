# I3WM-polybar
Here I have tried to create a i3wm polybar inspired by archcraft hack theme .
Polybar aims to help users build beautiful and highly customizable status bars for their desktop environment, without the need of having a black belt in shell scripting.

The main purpose of Polybar is to help users create awesome status bars. It has built-in functionality to display information about the most commonly used services. Some of the services included so far...

    Systray icons
    Window title
    Playback controls and status display for MPD using libmpdclient
    ALSA volume controls
    Workspace and desktop panel for bspwm and i3
    Workspace module for EWMH compliant window managers
    Keyboard layout and indicator status
    CPU and memory load indicator
    Battery display
    Network connection details
    Backlight level
    Date and time label
    Time-based shell script execution
    Command output tailing
    User-defined menu tree
    Inter-process messaging
    And more...
    
# Screanshots

![2023-01-18-225716_1920x1080_scrot](https://user-images.githubusercontent.com/82232181/213264586-7968c912-7f50-4afb-850e-05ca81968d75.png)
![2023-01-18-225813_1920x1080_scrot](https://user-images.githubusercontent.com/82232181/213264716-eae52667-5b69-4f47-a7c2-fb706fe6799f.png)




# Dependencies

Install following programs on your system before you use these themes.

    Polybar : Ofcourse, the bar itself
    Rofi : For App launcher, network, power and style menus
    pywal : For pywal support
    calc : For random colors support
    networkmanager_dmenu : For network modules

# Fonts

Here's a list of all fonts used by these themes.

Text Fonts

    Iosevka Nerd Font
    Fantasque Sans Mono
    Noto Sans
    Droid Sans
    Terminus

Icon Fonts

    Iosevka Nerd Font
    Icomoon Feather
    Material Icons
    Waffle (Siji)

# Installation

Follow the steps below to install these themes on your system.

First, Clone this repository -

    $ git clone --depth=1 https://github.com/SSKT7/I3WM-polybar.git

Change to cloned directory and make setup.sh executable -

    $ cd polybar-themes


    $ chmod +x setup.sh

Run setup.sh and select a style -

    $ ./setup.sh

    [*] Installing Polybar Themes...

    [*] Choose Style -
    [1] Simple
    [2] Bitmap

  [?] Select Option : 1

  [*] Installing fonts...
  [*] Creating a backup of your polybar configs...
  [*] Successfully Installed.

That's it, These themes are now installed on your system.

Note : These themes are like an ecosystem, everything here is connected with each other in some way. So... before modifying anything by your own, make sure you know what you are doing.

Launch the bar

To launch the bar with the selected theme, Just...

Open the terminal and enter the following command -

    $ bash ~/.config/polybar/launch.sh

Usage : launch.sh --theme

Available Themes :
--blocks    --colorblocks    --cuts      --docky
--forest    --grayblocks     --hack      --material
--panels    --pwidgets       --shades    --shapes

Now, select your theme and launch the bar -

    $ bash ~/.config/polybar/launch.sh --hack



Issues

# battery module issues

Go to module.ini and then change battery module accourding to your device .
To find suitable module for device use this command 

   /sys/class/power_supply/

# speed module issue
Go to module.ini and then change battery module accourding to your device .
To find suitable module for device use this command 

   ip a


Note : I'm working on other themes of archcraft, here i have uploaded one theme (hack).
Note : Make sure to remove your i3 bar and gaps from your i3 config.
