Irssi-Powerline
===============

An IRSSI theme with powerline goodness.

Screenshot
----------

  ![Irssi-Powerline](https://github.com/darac/irssi-powerline/raw/master/doc/Irssi%20Powerline.png)

Installation
------------

0. Clone the repository
  
  ```Shell
  git clone https://github.com/darac/irssi-powerline
  ```

1. Copy the theme to your .irssi config directory

  ```Shell
  cp irssi-powerline/solarized-powerline.theme ~/.irssi/
  ```

2. Copy adv_windowlist.pl into your scripts/autorun directory

  ```Shell
  cp irssi-powerline/scripts/autorun/*.pl ~/.irssi/scripts/autorun
  ```

3. If this is your first time using irssi, just copy the config file to your .irssi directory, otherwise, you will need to merge the changes (Basically, copy the `statusbar = { ... }` section across then, in settings ensure the fe-common/core and perl/core/scripts sections are copied over).
